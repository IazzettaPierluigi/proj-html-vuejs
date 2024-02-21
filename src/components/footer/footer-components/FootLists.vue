<script>


export default {
    name: "FootLists",



    data() {
        return {

        };
    },
    methods: {

    }
};
</script>

<template>
    <div class="container-fluid   ">
        <div class="row justify-content-center py-5 ">
            <div class="col-2 text-white ">
                <h2 class="text-uppercase">bookings</h2>
                <ul class="list-unstyled text-capitalize ">
                    <li>502 new design str, melbourne, san francisco, CA 94119, united states of america australia</li>

                    <li>t: 1 123-456-789</li>

                    <li>email: demo@example.com</li>

                    <li></li>
                </ul>
            </div>

            <div class="col-2 text-white ">
                <h2 class="text-uppercase">information</h2>
                <ul class="list-unstyled text-capitalize ">
                    <li>product support</li>

                    <li>checkout</li>

                    <li>report abuse</li>

                    <li>redeem voucher</li>

                    <li>order status</li>
                </ul>
            </div>

            <div class="col-2 text-white ">
                <h2 class="text-uppercase">support</h2>
                <ul class="list-unstyled text-capitalize ">
                    <li>policies & rules</li>

                    <li>privacy policy</li>

                    <li>license policy</li>

                    <li>my account</li>

                    <li>locality</li>
                </ul>
            </div>

            <div class="col-2 text-white ">
                <h2 class="text-uppercase">newsletter</h2>
                <div class="mb-3">

                    <input type="email" class="form-control bg-black border-secondary  " id="exampleFormControlInput1"
                        placeholder="Email">
                </div>
                <div class="mb-3">

                    <textarea class="form-control bg-black border-secondary  " id="exampleFormControlTextarea1" rows="3"
                        placeholder="Message"></textarea>

                </div>
                <div class="col-auto">
                    <button type="submit"
                        class="btn border border-primary rounded-0 px-5 text-white text-uppercase fw-bold btn-outline-primary   ">Send
                        message</button>
                </div>

            </div>
        </div>
    </div>
</template>

<style lang="scss" scoped>
@use "../../../styles/partials/variables" as *;

@use "../../../styles/partials/mixins" as *;
</style>