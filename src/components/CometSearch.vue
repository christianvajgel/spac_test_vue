<template>
    <div>
        <div style="position: relative">
            <b-navbar toggleable="lg" class="navbarTop" sticky style="border: 2px solid red; width: 100% !important;">
                <div style="border: 2px solid cornflowerblue; width: 100%">
                    <div style="width: inherit !important; justify-content: space-between !important; display: flex">
                        <div style="align-self: auto">
                            <b-navbar-brand href="#"><img src="../assets/img/home_icon_48px.png" height="24" width="24" alt="Home icon"/></b-navbar-brand>
                        </div>
                        <div style="align-self: center">
                            <b-img src="https://raw.githubusercontent.com/christianvajgel/spa_c_assets/master/images/logo_nav_header_100px.png" height="33" width="100" alt="spac logo navigation header"></b-img>
                        </div>
                        <div style="align-self: center">
                            <b-dropdown class="b-dropdown" size="sm" variant="outline-dark" toggle-class="text-decoration-none" no-caret dropleft>
                            <template v-slot:button-content>
                                <img src="https://raw.githubusercontent.com/christianvajgel/spa_c_assets/master/images/menu_icon_48px.png" height="24" width="24" alt="spac brand logo"/>
                            </template>
                            <b-dropdown-header class="dropdown-header">SPACE</b-dropdown-header>
                            <b-dropdown-item href="#">Comet Search</b-dropdown-item>
                            <b-dropdown-item href="#">Space Weather</b-dropdown-item>
                            <b-dropdown-item href="#">Picture of the day</b-dropdown-item>
                            <b-dropdown-header class="dropdown-header">MARS</b-dropdown-header>
                            <b-dropdown-item href="#">Mars Weather</b-dropdown-item>
                            <b-dropdown-item href="#">Photos</b-dropdown-item>
                            <b-dropdown-header class="dropdown-header">EARTH</b-dropdown-header>
                            <b-dropdown-item href="#">Overview</b-dropdown-item>
                            <b-dropdown-item href="#">Local Information</b-dropdown-item>
                            <b-dropdown-header class="dropdown-header">ISS</b-dropdown-header>
                            <b-dropdown-item href="#">Crew</b-dropdown-item>
                            <b-dropdown-item href="#">Current Location</b-dropdown-item>
                            <b-dropdown-item href="#">Pass Predictions</b-dropdown-item>
                            <b-dropdown-item href="#">Animated Map</b-dropdown-item>
                        </b-dropdown></div>
                    </div>
                </div>


<!--                <b-navbar-nav class="ml-auto" style="border: 2px solid cornflowerblue; flex-direction: row !important; justify-content: space-between !important">-->
<!--                    <b-dropdown class="b-dropdown" size="sm" variant="outline-dark" toggle-class="text-decoration-none" no-caret dropleft>-->
<!--                        <template v-slot:button-content>-->
<!--                            <img src="https://raw.githubusercontent.com/christianvajgel/spa_c_assets/master/images/menu_icon_48px.png" height="24" width="24" alt="spac brand logo"/>-->
<!--                        </template>-->
<!--                        <b-dropdown-header class="dropdown-header">SPACE</b-dropdown-header>-->
<!--                        <b-dropdown-item href="#">Comet Search</b-dropdown-item>-->
<!--                        <b-dropdown-item href="#">Space Weather</b-dropdown-item>-->
<!--                        <b-dropdown-item href="#">Picture of the day</b-dropdown-item>-->
<!--                        <b-dropdown-header class="dropdown-header">MARS</b-dropdown-header>-->
<!--                        <b-dropdown-item href="#">Mars Weather</b-dropdown-item>-->
<!--                        <b-dropdown-item href="#">Photos</b-dropdown-item>-->
<!--                        <b-dropdown-header class="dropdown-header">EARTH</b-dropdown-header>-->
<!--                        <b-dropdown-item href="#">Overview</b-dropdown-item>-->
<!--                        <b-dropdown-item href="#">Local Information</b-dropdown-item>-->
<!--                        <b-dropdown-header class="dropdown-header">ISS</b-dropdown-header>-->
<!--                        <b-dropdown-item href="#">Crew</b-dropdown-item>-->
<!--                        <b-dropdown-item href="#">Current Location</b-dropdown-item>-->
<!--                        <b-dropdown-item href="#">Pass Predictions</b-dropdown-item>-->
<!--                        <b-dropdown-item href="#">Animated Map</b-dropdown-item>-->
<!--                    </b-dropdown>-->
<!--                </b-navbar-nav>-->
            </b-navbar>

            <b-container>
                <b-row>
                    <b-col>
                        <b-img
                                src="https://raw.githubusercontent.com/christianvajgel/spa_c_assets/master/images/logo_600px.png"
                                fluid
                                height="192"
                                width="600"
                                alt="spac logo"
                                class="imgHome">
                        </b-img>
                    </b-col>
                </b-row>
                <b-row class="row justify-content-center">
                    <p class="sloganHome">Think outside the planet</p>
                </b-row>
            </b-container>

            <b-navbar toggleable="lg" class="navbarFooter" fixed="bottom">
                <b-navbar-brand href="#"><b-img src="https://raw.githubusercontent.com/christianvajgel/spa_c_assets/master/images/developer_icon_48px.png" height="24" width="24" alt="Home icon"/></b-navbar-brand>
                <p style="opacity: 0.25;margin-top: 20px;">Developed by Christian Vajgel</p>

                <b-navbar-nav class="ml-auto">
                    <b-nav>
                        <b-nav-item><a href="https://www.linkedin.com/in/christianvajgel/"><b-img class="iconFooter iconHover" src="https://raw.githubusercontent.com/christianvajgel/spa_c_assets/master/images/linkedin_logo_48px.png" height="24" width="24" alt="spac brand logo"/></a></b-nav-item>
                        <b-nav-item><a href="https://github.com/christianvajgel"><b-img class="iconFooter iconHover" src="https://raw.githubusercontent.com/christianvajgel/spa_c_assets/master/images/github_icon_48px.png" height="24" width="24" alt="spac brand logo"/></a></b-nav-item>
                        <b-nav-item><a href="https://t.me/vajgel"><b-img class="iconHover" src="https://raw.githubusercontent.com/christianvajgel/spa_c_assets/master/images/telegram_icon_48px.png" height="24" width="24" alt="spac brand logo"/></a></b-nav-item>
                    </b-nav>
                </b-navbar-nav>
            </b-navbar>

        </div>
    </div>
</template>

<script>
    export default {
        name: "CometSearch"
    }
</script>

<style>

</style>