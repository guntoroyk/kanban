<template>
  <nav class="navbar navbar-expand-lg navbar-dark bg-dark">
      <div class="container">
          <a class="navbar-brand" href="" @click.prevent="">KanbanQu</a>
          <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarSupportedContent" aria-controls="navbarSupportedContent" aria-expanded="false" aria-label="Toggle navigation">
              <span class="navbar-toggler-icon"></span>
          </button>

          <div class="collapse navbar-collapse" id="navbarSupportedContent">
              <ul class="navbar-nav ml-auto">
                  <li class="nav-item active">
                      <a class="nav-link" href="#" v-b-modal.modal-prevent-closing>New Task <span class="sr-only">(current)</span></a>
                  </li>
              </ul>
          </div>
      </div>
  </nav>
</template>

<script>
export default {
  name: 'Navbar'
}
</script>
