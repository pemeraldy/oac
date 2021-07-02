<template>
  <div>
    <div class="table-responsive">
      <table class="table">
        <thead>
          <tr>
            <th></th>
            <th>Topic</th>
            <th>Category</th>
            <th>Author</th>
            <th>Date</th>
            <th>Status</th>
            <th></th>
          </tr>
        </thead>
        <tr>
          <td>
            <input type="checkbox" aria-label="select topic" />
          </td>
          <td>Early Dectection of Cancer</td>
          <td>Cancer</td>
          <td>techymunhced</td>
          <td>12/06/2021</td>
          <td>
            <span class="badge badge-pill status-btn p-2">PENDING</span>
          </td>
          <td>
            <nuxt-link to="/">View</nuxt-link>
          </td>
        </tr>
        <tr>
          <td>
            <input type="checkbox" aria-label="select topic" />
          </td>
          <td>Early Dectection of Cancer</td>
          <td>Cancer</td>
          <td>techymunhced</td>
          <td>12/06/2021</td>
          <td>
            <span class="badge badge-pill status-btn p-2">PENDING</span>
          </td>
          <td>
            <nuxt-link to="/">View</nuxt-link>
          </td>
        </tr>
        <tr>
          <td>
            <input type="checkbox" aria-label="select topic" />
          </td>
          <td>Early Dectection of Cancer</td>
          <td>Cancer</td>
          <td>techymunhced</td>
          <td>12/06/2021</td>
          <td>
            <span class="badge badge-pill status-btn p-2">PENDING</span>
          </td>
          <td>
            <nuxt-link to="/">View</nuxt-link>
          </td>
        </tr>
      </table>
    </div>
  </div>
</template>

<script>
export default {};
</script>

<style scoped>
table {
  border-collapse: separate !important;
  border-spacing: 0;
}
.table th,
.table td {
  border: 0;
}
thead {
  background: rgba(231, 231, 237, 0.3);
}
tr th {
  font-size: 16px;
  font-weight: 600;
}
table tr {
  border-bottom-left-radius: 10px;
}
.status-btn{
  background: #FDE59B;
  width: 72px;
  font-weight: 600;
}
td a.nuxt-link{
  font-size: 12px;
}
</style>
