<template>
  <main class="page">
    <aside class="sidebar">
      <div class="brand">
        <img src="./assets/images/logo.png" class="brand__image" alt="Teams.co Logo" />
        <span class="brand__name ms-3">Teams.co</span>
      </div>

      <div class="profile">
        <img src="./assets/images/avatar.png" class="profile__image">

        <h4 class="profile__name">Aman</h4>
        <h5 class="profile__title">Product Designer</h5>
      </div>

      <ul class="nav">
        <li class="nav-item active">
          <a href="/" class="nav-item__link">
            <svg-icon name="dashboard" />

            <span class="nav-item__text">Dashboard</span>
          </a>
        </li>

        <li class="nav-item">
          <a href="#teams" class="nav-item__link">
            <svg-icon name="people" />
            <span class="nav-item__text">Teams</span>
          </a>
        </li>

        <li class="nav-item">
          <a href="#payments" class="nav-item__link">
            <svg-icon name="payments" />
            <span class="nav-item__text">Payments</span>
          </a>
        </li>

        <li class="nav-item">
          <a href="#attendance" class="nav-item__link">
            <svg-icon name="event" />
            <span class="nav-item__text">Attendance</span>
          </a>
        </li>

        <li class="nav-item">
          <a href="#settings" class="nav-item__link">
            <svg-icon name="settings" />
            <span class="nav-item__text">Settings</span>
          </a>
        </li>
      </ul>

      <div class="cta">
        <div class="cta__actions">
          <button class="btn btn-sm btn-icon">
            <svg-icon name="dots" width="21" height="34" />
          </button>
        </div>

        <div class="cta__image">
          <svg-icon name="group" width="54" height="54" />
        </div>

        <h4 class="cta__header">Create Teams</h4>
        <p class="cta__info">Increase your speed with more members</p>
      </div>
    </aside>

    <div class="content w-100 p-4 m-2">
      <header class="text-center">
        <h2 class="text-primary text-uppercase fw-bolder fs-6">qbricks</h2>

        <p class="mt-2 fw-bold fs-3">
          Sidebar One
        </p>

        <p class="mt-4 fs-5 text-muted">
          A pretty dark sidebar made with Bootstrap &amp; Vue 3.0
        </p>
      </header>

      <section class="mt-8">
        <div class="w-100 text-center">
          Credits: <a href="https://www.figma.com/community/file/1027182699498098492" target="_blank" rel="noopener" >Nickelfox Design</a>
        </div>
      </section>

      <footer class="text-center text-muted mt-4">
        <p>
          Made with
          <span class="text-vue">&hearts;</span>
          by <a href="https://github.com/schodevio" target="_blank" rel="noopener" class="author">schodevio</a>
          <br />
          2021
        </p>
      </footer>
    </div>
  </main>
</template>

<script>
import SvgIcon from './components/SvgIcon'

export default {
  name: 'qbrics-seidebar-one',
  components: { SvgIcon }
}
</script>
