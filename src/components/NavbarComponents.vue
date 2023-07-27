<script setup>
import { Navbar, NavbarLogo, NavbarCollapse, NavbarLink } from 'flowbite-vue'
</script>
<template>
    <Navbar>
      <template #logo>
        <NavbarLogo  image-url="public/PICTURES/pexels-photo-977846.jpeg">
        𝐂𝐨𝐟𝐟𝐞 𝐒𝐡𝐨𝐩
        </NavbarLogo>
      </template>
      <template #default="{isShowMenu}">
        <NavbarCollapse :isShowMenu="isShowMenu">
          <NavbarLink isActive link="#">Home</NavbarLink>
          <NavbarLink link="#">Layanan</NavbarLink>
          <NavbarLink link="#">Produk</NavbarLink>
          <NavbarLink link="#">Pesanan</NavbarLink>
          <NavbarLink link="#">Service</NavbarLink>
          <NavbarLink link="#">Pricing</NavbarLink>
          <NavbarLink link="#">Kontak</NavbarLink>
        </NavbarCollapse>
      </template>
    </Navbar>
</template>
