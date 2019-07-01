<template>
    <section id="topbar">
        <nav class="navbar" role="navigation" aria-label="main navigation">
            <div class="navbar-brand">
                <a class="navbar-item" href="/">
                    <img src="~/assets/logo-v2.1.png">
                </a>
            </div>
        </nav>
    </section>
</template>

<script>
export default {
  components: {}
}
</script>

<style scoped>
#topbar nav{
    background: #F0F0F0;
    -webkit-box-shadow: 0px 4px 4px 1px  rgba(224,224,224,1);
    -moz-box-shadow: 0px 4px 4px 1px  rgba(224,224,224,1);
    box-shadow: 0px 4px 4px 1px rgba(224,224,224,1);
}
#topbar .navbar img {
    padding: 10px;
    max-height: 50px;
}
</style>