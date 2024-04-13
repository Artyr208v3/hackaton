<script lang="ts">
	import Pagination from './../../lib/components/UI/Pagination.svelte';
	import List from './../../lib/components/widgets/List.svelte';
    import Header from '$lib/components/widgets/header.svelte';
    
        let source: string = "/logo.png"
        </script>
    
    <Header source={source}/>
    <List/>
    <div class="pagination">
        <Pagination/>
    </div>
    
    <style>
        .pagination {
            display: flex;
            justify-content: center;
            margin-top: 50px;
        }
    </style>
