<template>
  <div class="about-card">
    <div class="card-title">
      <img src="../assets/vue.png" alt="logo" class="avatar" height="50px">
      <div class="title-text-content">
        <p>About me</p>
        <h2>Antoine Combe</h2>
      </div>
    </div>
    <div class="card-content">
      <p>Lorem, ipsum dolor sit amet consectetur adipisicing elit. Amet reiciendis vero exercitationem quis repellat? Quis, totam obcaecati quod eveniet aliquid deleniti quos. Quam quo maiores perspiciatis id debitis soluta possimus!</p>
    </div>
    <table>
      <tr>
      <th>Requirement</th>
      <th>Solution</th>
      </tr>
      <tr>
        <td>Design</td>
        <td>Photoshop...</td>
      </tr>
      <tr>
        <td>Design</td>
        <td>Photoshop...</td>
      </tr>
      <tr>
        <td>Design</td>
        <td>Photoshop...</td>
      </tr>
    </table>
    <p>Lorem ipsum dolor sit amet consectetur, adipisicing elit. Tempore excepturi perspiciatis eos repellat praesentium aspernatur molestiae quidem in quos placeat nulla modi, accusamus ratione animi optio sapiente quas vel ex.</p>
    <p>Lorem, ipsum dolor sit amet consectetur adipisicing elit. Quod, saepe, deleniti animi minus nulla earum sit maiores officia sapiente excepturi repellat modi nesciunt dolorum consectetur amet voluptas facere asperiores nobis?</p>
  </div>
</template>

<style lang="sass" scoped>
  .about-card
    background: #333
    padding: 3em
    border-radius : 10px
    color: white
    .card-title
      display: flex
      align-items: center
      background: #222
      border-radius : 10px
      .avatar
        border 1px solid rgba(255, 255, 255, 0.4)
        border-radius: 50%
        margin: 0 30px
    .title-text-content
      p
        margin-bottom: 0
        rgba(210,210,210)
      h2
        margin-top: 0
  .card-content p
    line-height: 1.5
    margin: 30px auto

</style>
