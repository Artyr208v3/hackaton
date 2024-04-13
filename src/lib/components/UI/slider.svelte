
<div class="photo_album">
    <div class="slider">
        <img src="/slider2.png" alt="" class="slider2">
        <img src="/slider1.png" alt="" class="slider1">
        <img src="/slider3.png" alt="" class="slider3">
    </div>
</div>

<style>
    .slider {
        display: flex;
        position: static;
        justify-content: center;
        align-items: flex-end;
    }
    .slider1 {
        width: 428px;
        height: 230px;
    }
    .slider2 {
        position: relative;
        left: 20px;
        top: -15px;
        z-index: -1;
        height: 162px;
        opacity: 50%;
    }
    .slider3 {
        position: relative;
        left: -20px;
        top: -15px;
        z-index: -1;
        height: 162px;
        opacity: 50%;
    }

    @media (max-width: 480px) {
        .slider {
            display: none;
        }
    }
</style>