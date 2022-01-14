<template>
    <div class="page-cart">
        <div class="columns is-multiline">
            <div class="column is-12">
                <h1 class="title">Your Cart</h1>
            </div>
            <div class="column is-12 box">
                <table class="table is-fullwidth" v-if="cartTotalLength">
                    <thead>
                        <tr>
                            <th>Product</th>
                            <th>Price</th>
                            <th>Quantity</th>
                            <th>Total</th>
                            <th></th>
                        </tr>
                    </thead>

                    <tbody>
                        
                    </tbody>
                </table>

                <p v-else>You don't have any products in your cart...</p>
            </div>
        </div>
    </div>    
</template>

<script>
import axios from 'axios'

export default {
    name: 'Cart'
}
</script>