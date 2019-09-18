<template>
  <div class="about-card">
    <div class="card-title">
      <img src="../assets/polylogo-neck.png" alt="avatar" class="avatar" width="75px" height="75px">
      <div class="title-text-content">
        <p>About me</p>
        <h2>Jenn Tillman</h2>
      </div>
    </div>

    <div class="card-content">
        <p>
            I am currently learning to be a Front-End Web Developer with an interest in Quality Assurance and Testing. I am also a Twitch Affiliate and stream very consistently. Playing video games and interacting with others is a passion of mine. In addition to those focuses I am also passionate about learning and understanding as much as I can about myself, others, and the world around me. I see this as a constant and continuous process. 
        </p>
        <table width="100%">
          <tr>
            <th>Requirement</th>
            <th>Solution</th>
          </tr>
          <tr>
            <td>Design</td>
            <td>Gimp, Inkscape, Figma</td>
          </tr>
          <tr>
              <td>Front-End</td>
              <td>HTML5, CSS3, JavaScript, React.js, Vue.js</td>
          </tr>
          <tr>
              <td>Back-End</td>
              <td>Node.js, Express.js, MySQL, GraphQL</td>
          </tr>
        </table>
        <p>
          My hope is to work as a QA Analyst where I can have a more of an overview perspective on many technologies and learn to test, identify, and log bugs. Essentially, help discover and solve problems in the Web Development processes. 
        </p>
    </div>
  </div>
</template>

// We do not want this to be seen by any of the other views / components
<style lang="sass" scoped>
  .about-card
    background: #333
    padding: 3em
    border-radius: 10px 
    color: white

  .about-card > .card-title
    display: flex
    align-items: center
    background: #222
    border-radius: 10px
    .avatar
      border: 1px solid rgba(255,255,255, 0.4)
      border-radius: 50%
      margin: 0 30px

  .title-text-content
    p
      margin-bottom: 0
      rgb(205, 205, 205)
    h2
      margin-top: 0

  .card-content p 
    line-height: 1.5
    margin: 30px auto

  table
    border-spacing: 0px
    margin: 50px auto
    tr th, tr td
      border: 1px solid white
      border-top: none
      padding: 10px
      text-align: center
      &:first-of-type
        border-left: none
      &:nth-of-type(2)
        border-right: none

</style>
