<template>
  <b-container>
    <br />
    <h4 align="center">แบบบันทึกข้อมูลการสืบพันธุ์ของแม่พันธุ์</h4>

    <br />
    <p5>วัน/เดือน/ปี ที่ผสมพันธุ์</p5>
    <b-form-input v-model="text" placeholder=""></b-form-input>
    <p5>พ่อที่ใช้ผสมพันธุ์</p5>
    <b-form-input v-model="text" placeholder=""></b-form-input>
    <p5>อายุเมื่อผสมพันธุ์ </p5>
    <b-form-input v-model="text" placeholder=""></b-form-input>
    <p5>กำหนดวันคลอด</p5>
    <b-form-input v-model="text" placeholder=""></b-form-input
    ><br />
    <h3>ลูกที่เกิด</h3>
    <p5>วัน/เดือน/ปี</p5>
    <b-form-input v-model="text" placeholder=""></b-form-input>
    <p5>หมายเลข</p5>
    <b-form-input v-model="text" placeholder=""></b-form-input>
    <p5>เพศ</p5>
    <b-form-input v-model="text" placeholder=""></b-form-input>

    <p5>หมายเหตุ</p5>
    <b-form-input v-model="text" placeholder=""></b-form-input>
    <br />
    <b-button variant="success">บันทึก</b-button>
  </b-container>
</template>

<script></script>
