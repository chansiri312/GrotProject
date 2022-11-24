<template>
  <b-container>
    <br />
    <h4 align="center">ตารางการจัดการข้อมูลแพะ</h4>
    <br />
    <p5>หมายเลขแพะนม</p5>
    <b-form-input v-model="text1" placeholder=""></b-form-input>

    <p5>เพศ</p5>
    
    <b-row>
    <b-form-radio-group 
      v-model="selected"
      :options="options"
      value-field="item"
      text-field="name"
      disabled-field="notEnabled"
    ></b-form-radio-group>
   </b-row>
   <br />
 
    <p5>พันธุ์</p5>
    <b-form-input v-model="text2" placeholder=""></b-form-input>
    <p5>วัน/เดือน/ปี เกิด</p5>
    <b-form-input v-model="text3" placeholder=""></b-form-input>
    <p5>น้ำหนักแรกเกิด (Kg)</p5>
    <b-form-input v-model="text4" placeholder=""></b-form-input>
    <p5>หมายเลขพ่อ/ชื่อ</p5>
    <b-form-input v-model="text5" placeholder=""></b-form-input>
    <p5>หมายเลขแม่/ชื่อ</p5>
    <b-form-input v-model="text6" placeholder=""></b-form-input>
    <p5>วัน/เดือน/ปี หย่านม</p5>
    <b-form-input v-model="text7" placeholder=""></b-form-input>
    <p5>น้ำหนักหย่านม (Kg)</p5>
    <b-form-input v-model="text8" placeholder=""></b-form-input>
    <p5>หมายเหตุ</p5>
    <b-form-input v-model="text9" placeholder=""></b-form-input>
    <br />
    <b-button variant="success">บันทึก</b-button>
  </b-container>
</template>

<script>
export default {
  data() {
    return {
      options: [
        { item: "A", name: "เพศผู้" },
        { item: "B", name: "เพศเมีย" },
      ],
    };
  },
};
</script>
