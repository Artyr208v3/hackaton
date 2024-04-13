<script>
	import Slider from './../UI/slider.svelte';
	import SuperHumans from './../UI/super_humans.svelte';
	import AboutUi from '../UI/about_ui.svelte';
	import Author from '../UI/author.svelte';
</script>

<main>
	<AboutUi />
	<p class="text_history">
		<b>История праздника</b><br /> День космонавтики — отмечаемая сначала в СССР, а после в России и
		других странах постсоветского пространства 12 апреля дата, установленная в ознаменование первого
		полёта человека в космос. 12 апреля 1961 года советский космонавт Юрий Гагарин на космическом
		корабле «Восток-1» стартовал с космодрома «Байконур» и впервые в мире совершил орбитальный облёт
		планеты Земля. Полёт в околоземном космическом пространстве продлился 108 минут. <br /> В работах
		над созданием космического корабля и ракеты-носителя, подготовкой к запуску и обеспечением полёта
		корабля с человеком на борту принимали участие коллективы более 100 организаций. Среди них – возглавляемые
		Главным теоретиком отечественной космонавтики академиком М.В. Келдышем, академиками В.П. Глушко,
		В.П. Барминым, Н.А. Пилюгиным, В.И. Кузнецовым, членом-корреспондентом АН СССР М.С. Рязанским.
	</p>
	<Author/>
    <SuperHumans/>
    
</main>
<footer>
    <p class="author_name">Фотоальбом</p>
    <Slider/>
</footer>


<style>
	@import url('https://fonts.googleapis.com/css2?family=Roboto:ital,wght@0,100;0,300;0,400;0,500;0,700;0,900;1,100;1,300;1,400;1,500;1,700;1,900&display=swap');
	footer {
        display: flex;
        flex-direction: column;
        align-items: center;
        justify-content: center;
        border: 1px solid #E7E7E7;
    }
    main {
		display: grid;
		grid-template-columns: 1fr 1fr;
		grid-template-rows: 1fr 1fr;
		border: 1px solid #e7e7e7;
	}
	.text_history {
		margin: 15px;
		font-size: 18px;
		font-family: 'Roboto', sans-serif;
		font-weight: 400;
		font-style: normal;
	}
    .author_name {
        width: 120px;
        font-family: 'Roboto', sans-serif;
		font-weight: 400;
		font-style: normal;
        border: 1px solid #E7E7E7;
        border-top: none;
        font-size: 18px;
        margin: 0;
        border-radius: 0 0 10px 10px;
        padding: 2px 30px 2px 30px;
        margin-bottom: 20px;
        
    }

	@media (max-width: 480px) {
		main {
			display: flex;
			flex-direction: column;
		}
		.author_name {
			display: none;
		}
	}
    
</style>
