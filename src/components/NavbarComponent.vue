<script setup>
import { Navbar, NavbarLogo, NavbarCollapse, NavbarLink } from 'flowbite-vue'
</script>
<template>
    <Navbar solid>
      <template #logo>
        <NavbarLogo link="https://www.google.com/" alt="Flowbite logo" image-url="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcTLmV-ULpUaMJJHRf7T3vFrDRrmwOkNJzQZAMOdc6hD8CR1C34o2QqI61-z4VWA5FiT-TI&usqp=CAU">
          PORTOFOLIO
        </NavbarLogo>
      </template>
      <template #default="{isShowMenu}">
        <NavbarCollapse :isShowMenu="isShowMenu">
          <NavbarLink is-active>BERANDA</NavbarLink>
          <NavbarLink>TENTANG</NavbarLink>
          <NavbarLink>KONTAK</NavbarLink>
          <!-- <NavbarLink>PORTOFOLIO</NavbarLink> -->
        </NavbarCollapse>
      </template>
    </Navbar>
</template>
