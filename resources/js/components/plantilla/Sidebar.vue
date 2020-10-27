<template>
    <aside class="main-sidebar sidebar-dark-primary elevation-4">
        <!-- Brand Logo -->

        <span class="brand-text font-weight-light">AdminLTE 3</span>
        

        <!-- Sidebar -->
        <div class="sidebar">
        <!-- Sidebar user (optional) -->
        <div class="user-panel mt-3 pb-3 mb-3 d-flex">
            <div class="image">
            <img  class="img-circle elevation-2" alt="User Image">
            </div>
            <div class="info">
            <a href="#" class="d-block">Sistema</a>
            </div>
        </div>

        <!-- Sidebar Menu -->
        <nav class="mt-2">
            <ul class="nav nav-pills nav-sidebar flex-column" data-widget="treeview" role="menu" data-accordion="false">
            <!-- Add icons to the links using the .nav-icon class
                with font-awesome or any other icon font library -->
            <li class="nav-item has-treeview">
                <router-link class="nav-link active" :to="'/'">
                    <i class="nav-icon fas fa-tachometer-alt"></i>
                    <p>
                    Dashboard
                    </p>
                </router-link>
            </li>

            <li class="nav-header">Ventas</li>
            <li class="nav-item">
                <router-link class="nav-link" :to="'/pedido'">
                <i class="nav-icon far fa-calendar-alt"></i>
                <p>
                    Pedido
                    <span class="badge badge-info right">2</span>
                </p>
                </router-link>
            </li>
            <li class="nav-item">
                <router-link class="nav-link" :to="'/cliente'">
                <i class="nav-icon far fa-image"></i>
                <p>
                    Cliente
                </p>
                </router-link>
            </li>

            <li class="nav-header">Almacen</li>
            <li class="nav-item">
                <router-link class="nav-link" :to="'/producto'">
                <i class="nav-icon far fa-calendar-alt"></i>
                <p>
                    Producto
                    <span class="badge badge-info right">2</span>
                </p>
                </router-link>
            </li>
            <li class="nav-item">
                <router-link class="nav-link" :to="'/categoria'">
                <i class="nav-icon far fa-image"></i>
                <p>
                    Categorias
                </p>
                </router-link>
            </li>

            <li class="nav-header">Administracion</li>
            <li class="nav-item">
                <router-link class="nav-link" :to="'/usuario'">
                <i class="nav-icon far fa-calendar-alt"></i>
                <p>
                    Usuarios
                    <span class="badge badge-info right">2</span>
                </p>
                </router-link>
            </li>
            <li class="nav-item">
                <router-link class="nav-link" :to="'/rol'">
                <i class="nav-icon far fa-image"></i>
                <p>
                    Roles
                </p>
                </router-link>
            </li>
            <li class="nav-item">
                <router-link class="nav-link" :to="'/permiso'">
                <i class="nav-icon far fa-image"></i>
                <p>
                    Permisos
                </p>
                </router-link>
            </li>
            <li class="nav-header">Reportes</li>
            <li class="nav-item">
                <router-link class="nav-link" :to="'/reportes'">
                <i class="nav-icon far fa-calendar-alt"></i>
                <p>
                    Reportes
                    <span class="badge badge-info right">2</span>
                </p>
                </router-link>
            </li>

            </ul>
        </nav>
        <!-- /.sidebar-menu -->
        </div>
        <!-- /.sidebar -->
    </aside>
</template>

<script>
export default {

}
</script>

<style>

</style>