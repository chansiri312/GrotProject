<template>
  <b-container>
    <br />
    <h4 align="center">แบบบันทึกข้อมูลประวัติการให้ผลผลิต <br /> (รายตัว)</h4>

    <br />
    <p5>หมายเลขแพะ</p5>
    <b-form-input v-model="text" placeholder=""></b-form-input>
    <br />
    <h3>ปริมาณน้ำนม (Kg)</h3>
    <p5>เช้า</p5>
    <b-form-input v-model="text" placeholder=""></b-form-input>
    <p5>เย็น </p5>
    <b-form-input v-model="text" placeholder=""></b-form-input>
    <p5>รวม</p5>
    <b-form-input v-model="text" placeholder=""></b-form-input>
    <p5>หมายเหตุ</p5>
    <b-form-input v-model="text" placeholder=""></b-form-input>
    <br />
    <b-button variant="success">บันทึก</b-button>
  </b-container>
</template>

<script></script>
