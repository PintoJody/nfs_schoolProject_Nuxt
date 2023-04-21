<template>

    <div>
      <b-navbar type="dark" variant="dark">
        <b-navbar-nav>
          <b-nav-item href="#">Accueil</b-nav-item>
    
          <!-- Navbar dropdowns -->
          <b-nav-item-dropdown text="Classes" right>
            <b-dropdown-item href="#">1BCI</b-dropdown-item>
          </b-nav-item-dropdown>
    
        </b-navbar-nav>
      </b-navbar>
    </div>
    
    </template>
    
    <script>
        export default {
            name: 'Navbar',
        }
    </script>