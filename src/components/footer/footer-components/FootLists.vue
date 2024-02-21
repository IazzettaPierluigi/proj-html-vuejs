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
                    <li><a href="">502 new design str, melbourne, san francisco, CA 94119, united states of america
                            australia</a></li>

                    <li><a href="">t: 1 123-456-789</a></li>

                    <li><a href="">email: demo@example.com</a></li>

                    <li></li>
                </ul>
            </div>

            <div class="col-2 text-white ">
                <h2 class="text-uppercase">information</h2>
                <ul class="list-unstyled text-capitalize ">
                    <li><a href="">product support</a></li>

                    <li><a href="">checkout</a></li>

                    <li><a href="">report abuse</a></li>

                    <li><a href="">redeem voucher</a></li>

                    <li><a href="">order status</a></li>
                </ul>
            </div>

            <div class="col-2 text-white ">
                <h2 class="text-uppercase">support</h2>
                <ul class="list-unstyled text-capitalize ">
                    <li><a href=""> policies & rules</a></li>

                    <li><a href="">privacy policy</a></li>

                    <li><a href="">license policy</a></li>

                    <li><a href="">my account</a></li>

                    <li><a href="">locality</a></li>
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


li {
    a {
        text-decoration: none;
    }
}

li:hover {
    color: #f2870c;
}
</style>