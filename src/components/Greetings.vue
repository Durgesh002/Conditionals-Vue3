<template>
    <div class="container">
        <div class="row">
            <div class="col-md-5">
                <div class="card">
                    <div class="card-body">
                        <p class="h3">Hello {{ msg }}</p>
                        <button class="btn btn-success m-1" @click="greet('Good Morning')">Good Morning</button>
                        <button class="btn btn-warning m-1" @click="greet('Good Afternoon')">Good Afternoon</button>
                        <button class="btn btn-danger m-1" @click="greet('Good Evening')">Good Evening</button>
                    </div>
                </div>
            </div>
        </div>
    </div>
</template>

<script>
    export default {
        name: 'Greetings',
        data: function(){
            return{
                msg: ""
        }
        },
        methods: {
            greet : function(val){
                this.msg = val
            }
        }
    }
</script>

<style scoped>

</style>