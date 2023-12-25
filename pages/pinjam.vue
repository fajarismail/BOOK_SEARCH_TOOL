<template>
            <nav class="navbar">
                <div class="container-fluid">
                    <a class="navbar-brand">DATA PEMINJAM</a>
                    <form class="d-flex" role="search">
                        <NuxtLink to="/" class="btn btn-dak"><button type="button" class="btn-close btn-close-black"
                aria-label="Close"></button></NuxtLink>
                    </form>
                </div>
            </nav>

  <div class="container m-5">
    <div class="input-group m-4">
      <input
        type="text"
        class="form-control"
        aria-label="Sizing example input"
        aria-describedby="inputGroup-sizing-default"
        placeholder="NAMA KAMU"
      />
    </div>
    <div class="input-group m-4">
      <input
        type="text"
        class="form-control"
        aria-label="Sizing example input"
        aria-describedby="inputGroup-sizing-default"
        placeholder="KELAS KAMU"
      />
    </div>
    <div class="input-group m-4">
      <input
        type="text"
        class="form-control"
        aria-label="Sizing example input"
        aria-describedby="inputGroup-sizing-default"
        placeholder="JUDUL BUKU"
      />
  </div>
    <div>
        TANGGAL MEMINJAM
    </div>
    <div class="input-group m-4">
      <input
        type="date"
        class="form-control"
        aria-label="Sizing example input"
        aria-describedby="inputGroup-sizing-default"
      />
    </div>
    <div>
        TANGGAL PENGEMBALIAN
    </div>
    <div class="input-group m-4">
      <input
        type="date"
        class="form-control"
        aria-label="Sizing example input"
        aria-describedby="inputGroup-sizing-default"
      />
    </div>

</div>
<div class="row">
    <div class="col-9">

    </div>
    <div class="col">
        <NuxtLink to="/" class="btn btn-dak mr-5"><button type="button" class="btn btn-primary btn-lg">PINJAM BUKU</button></NuxtLink>

    </div>
</div>
</template>
<style>
.navbar {
  background-color: rgb(0, 47, 255);
}
</style>