<template>
    <h1>ListPage</h1>
    <TablePage/>
</template>
<script>
import TablePage from '@/components/Table.vue'
export default {
    name: 'ListPage',
    components: {
        TablePage
    },
    data(){
        return {
            header:[
                {id:1,name:'id'},
                {id:2,name:'name'},
                {id:3,name:'link'},
            ],
            body:[
                {id:1,name:'test1',link:true},
                {id:2,name:'test2',link:false},
                {id:3,name:'test3',link:true},
            ],
        }
    }
}
</script>
<style>
</style>