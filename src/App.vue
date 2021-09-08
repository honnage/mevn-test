
<template>
  <div>
    <!-- Nav bar -->  
    <nav class="navbar navbar-expand-sm bg-dark navbar-dark fixed-top"> 
      <div class="container">
        <router-link to="/" class="navbar-brand float-left">MEVN Stack CRUD</router-link>
        <ul class="nav navbar-nav flex-row float-right">
          <li class="nav-item">
            <router-link to="/" class="pr-3 nav-link">Create Student</router-link>
          </li>
          <li class="nav-item">
            <router-link to="/view" class="pr-3 nav-link">View Students</router-link>
          </li>
        </ul>
      </div>
    </nav>

    <!-- Router view -->
    <div class="container mt-5">
      <router-view></router-view>
    </div>
  </div>
</template>