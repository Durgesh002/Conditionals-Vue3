<template>
    <div class="container">
        <div class="row">
            <div class="col md-4">
                <div class="card-body">
                    <p class="h3 display-4">{{count}}</p>
                    <button class="btn btn-success m-1" @click="inc">Increment</button>
                    <button class="btn btn-primary m-1" @click="dec">Decrement</button>
                </div>
            </div>
        </div>
    </div>
</template>

<script>
    export default {
        name: 'Counter',
        data: function() {
            return{
                count : 0
            }
        },
        methods: {
            inc: function(){
                return this.count+=1
            },
            dec: function(){
                return this.count-=1
            }
        }
    }
</script>

<style scoped>

</style>