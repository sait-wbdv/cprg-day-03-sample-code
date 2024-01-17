<template>
  <main>
    <header>
      <h1 class="main-heading">Sign up Form</h1>
    </header>
    <section>
      <h2>Form Example</h2>
      <form>
        <div class="form-example">
          <label for="name">Enter your name: </label>
          <input type="text" name="name" id="name" required />
        </div>
        <div class="form-example">
          <label for="email">Enter your email: </label>
          <input type="email" name="email" id="email" required />
        </div>
        <div class="form-example">
          <label for="password">Enter your password: </label>
          <input type="password" name="password" id="password" required />
        </div>
        <div class="form-example">
          <input type="submit" value="Subscribe!" />
        </div>
      </form>
    </section>
  </main>
</template>
