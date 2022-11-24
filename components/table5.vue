<template>
  <b-container>
    <br />
    <h4 align="center">แบบบันทึกข้อมูลการการรับ-จ่ายเวชภัณฑ์และสารเคมี</h4>

    <br />
    <p5>ชื่อของเวชภัณฑ์</p5>
    <b-form-input v-model="text" placeholder=""></b-form-input>
    <p5>สารเคมี</p5>
    <b-form-input v-model="text" placeholder=""></b-form-input>

    <b-row>
      <b-col
        ><p5>จำนวนที่ซื้อ/ยกมา </p5>
        <b-form-input v-model="text" placeholder=""></b-form-input
      ></b-col>
      <b-col
        ><p5> วัน/เดือน/ปี</p5
        ><b-form-input v-model="text" placeholder=""></b-form-input
      ></b-col>
    </b-row>

    <b-row>
      <b-col
        ><p5>จำนวนที่ใช้ วัน/เดือน/ปี </p5>
        <b-form-input v-model="text" placeholder=""></b-form-input
      ></b-col>
      <b-col
        ><p5> วัน/เดือน/ปี</p5
        ><b-form-input v-model="text" placeholder=""></b-form-input
      ></b-col>
    </b-row>

    <p5>คงเหลือ</p5>
    <b-form-input v-model="text" placeholder=""></b-form-input>
    <p5>หมายเหตุ</p5>
    <b-form-input v-model="text" placeholder=""></b-form-input>
    <br />
    <b-button variant="success">บันทึก</b-button>
  </b-container>
</template>

<script></script>
