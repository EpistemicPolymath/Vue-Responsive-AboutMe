<template>
    <section class="nav">
        <div class="nav-logo">
            <img src="../assets/polylogo.png" alt="logo" height="100px" width="100px">
            <p>EpistemicPolymath</p>
        </div>
        <div class="nav-menu">
            <ul class="nav-menu-list">
                <li class="nav-list-item"><a href="/">About me</a></li>
                <li class="nav-list-item"><a target="_blank" href="https://github.com/EpistemicPolymath">GitHub</a></li>
            </ul>
        </div>
    </section>
</template>


<script>
export default {
    
}
</script>

<style lang="sass" scoped>
    .nav
        position: fixed
        left: 0
        top: 0
        bottom: 0
        background: #333
        display: flex
        flex-direction: column
        align-items: center
        width: 20vw
        .nav-logo
            margin: 100px auto
            color: white
            display: flex
            flex-direction: column
            align-items: center
        .nav-menu
            color: white
    .nav-menu-list
        list-style: none
        padding: 0
        .nav-list-item
            background: #222
            padding: 10px 20px
            text-align: center
            margin: 10px auto
            cursor: pointer
            &:hover
                width: 100%
            a 
                text-decoration: none
                color: white

</style>