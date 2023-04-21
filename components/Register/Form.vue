<template>

    <form>
        <div class="form-group">
            <label for="username">Nom</label>
            <input type="text" class="form-control" id="username" placeholder="John Doe">
        </div>
        <div class="form-group">
            <label for="email">Email</label>
            <input type="email" class="form-control" id="email" placeholder="exemple@gmail.com">
        </div>
        <div class="form-group">
            <label for="password">Mot de passe</label>
            <input type="password" class="form-control" id="password" placeholder="*******">
        </div>

        <button type="submit" class="btn btn-primary">Envoyer</button>
    </form>

</template>

<script lang="ts">
  
    export default {
      name: 'registerForm',
    }
    </script>