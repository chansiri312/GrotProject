<template>
    <b-container>
      <br />
      <h4 align="center">แบบบันทึกข้อมูลการใช้วัคซีน-การถ่ายพยาธิ <br />(ทั้งฝูง)</h4>
  
      <br />
      <p5>วัน/เดือน/ปี</p5>
      <b-form-input v-model="text" placeholder=""></b-form-input>
      <p5>คอก/ฝูง</p5>
      <b-form-input v-model="text" placeholder=""></b-form-input>
  <h3>การใช้วัคซีน</h3>
      <b-row>
        <b-col
          ><p5>ชนิด/ชื่อวัคซีน </p5>
          <b-form-input v-model="text" placeholder=""></b-form-input
        ></b-col>
        <b-col
          ><p5> จำนวนแพะ (ตัว)</p5
          ><b-form-input v-model="text" placeholder=""></b-form-input
        ></b-col>
      </b-row>
      <h3>การถ่ายพยาธิ</h3>
      <b-row>
        <b-col
          ><p5>ชนิด/ชื่อยา </p5>
          <b-form-input v-model="text" placeholder=""></b-form-input
        ></b-col>
        <b-col
          ><p5> จำนวนโค (ตัว)</p5
          ><b-form-input v-model="text" placeholder=""></b-form-input
        ></b-col>
      </b-row>
  
      <p5>การตรวจโรคบรูเซลโลซีล</p5>
      <b-form-input v-model="text" placeholder=""></b-form-input>
      <p5>ผู้ปฏิบัติงาน</p5>
      <b-form-input v-model="text" placeholder=""></b-form-input>
      <p5>ผู้ควบคุม</p5>
      <b-form-input v-model="text" placeholder=""></b-form-input>
      <br />
      <b-button variant="success">บันทึก</b-button>
    </b-container>
  </template>
  
  <script></script>
  