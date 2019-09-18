<template>
    <section class="nav">
        <div class="nav-logo">
            <img src="../assets/polylogo.png" alt="logo" height="160px" width="160px">
            <p>EpistemicPolymath</p>
        </div>
        <div class="nav-menu">
            <ul class="nav-menu-list">
                <li class="nav-list-item">About me</li>
                <li class="nav-list-item">GitHub</li>
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
        background: #333
        display: flex
        flex-direction: column
        justify-content: space-around
        align-items: center
        .nav-logo
            margin: 20px auto
            color: white
            display: flex
            flex-direction: column
            align-items: center
            font-size: 2em
        .nav-menu
            width: 100%

    .nav-menu-list
        list-style: none
        padding: 0
        display: flex
        margin: 0
        color: white
        li
          width: 50%
          text-align: center
          background: #555
          padding: 10px 0
          cursor: pointer
          transition: background 300ms ease-in-out
          &:hover
              background: #333
          &:first-of-type
              border-bottom: 5px solid #222
</style>