<template>
  <b-container>
    <br />
    <h4 align="center">แบบบันทึกข้อมูลประวัติการให้ผลผลิต <br />(รายฟาร์ม)</h4>

    <br />
    <p5>หมายเลขประจำตัว</p5>
    <b-form-input v-model="text" placeholder=""></b-form-input>

    <p5>ครั้งทีของการให้นม</p5>
    <b-form-input v-model="text" placeholder=""></b-form-input>
    <p5>จำนวนวันให้ผลผลิต (วัน)</p5>
    <b-form-input v-model="text" placeholder=""></b-form-input>
    <p5>ปริมาณน้ำนม (Kg)</p5>
    <b-form-input v-model="text" placeholder=""></b-form-input>
    <p5>หมายเหตุ</p5>
    <b-form-input v-model="text" placeholder=""></b-form-input>

    <br />
    <b-button variant="success">บันทึก</b-button>
  </b-container>
</template>

<script></script>
