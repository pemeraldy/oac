<template>
  <div>
    <div class="table-responsive">
      <table class="table">
        <thead>
          <tr>
            <th></th>
            <th>Email address</th>
            <th>Username</th>
            <th>Role</th>
            <th>Status</th>
            <th>Action</th>
            <th></th>
          </tr>
        </thead>
        <tr>
          <td>
            <input type="checkbox" aria-label="select topic" />
          </td>
          <td>yopee@gmail.com</td>
          <td>Admin</td>
          <td>techymunhced</td>
          
          <td>
            <span class="badge badge-pill status-btn active p-2">Active</span>
          </td>
          <td class="action">
            BLOCK USER
          </td>
        </tr>
        <tr>
          <td>
            <input type="checkbox" aria-label="select topic" />
          </td>
          <td>yopee@gmail.com</td>
          <td>Admin</td>
          <td>techymunhced</td>          
          <td>
            <span class="badge badge-pill status-btn p-2">Active</span>
          </td>
          <td class="action blocked">
            BLOCK USER
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
  cursor: pointer;
  background: #F37D7D;
  width: 72px;
  font-weight: 600;
  color: #fff;
  text-transform: uppercase;
}
.status-btn.active{
  background: #48D784;
  width: 72px;
  font-weight: 600;
}
td.action{
  cursor: pointer;
  font-size: 12px;
  font-weight: 600;
}
td.action.blocked{
  color: #F37D7D;
}
td.action{
  color:#48D784;
  ;
}
</style>
