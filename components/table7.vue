<template>
  <b-container>
    <br />
    <h4 align="center">แบบบันทึกข้อมูลการรักษาโรค</h4>

    <br />
    <p5>วัน/เดือน/ปี</p5>
    <b-form-input v-model="text" placeholder=""></b-form-input>
    <p5>หมายเลขประจำตัว</p5>
    <b-form-input v-model="text" placeholder=""></b-form-input>

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

    <p5> ข้อมูลสุขภาพ</p5
    ><b-form-input v-model="text" placeholder=""></b-form-input>

    <p5>การรักษาและผลการรักษา </p5>
    <b-form-input v-model="text" placeholder=""></b-form-input>

    <p5> ผู้รักษา</p5
    ><b-form-input v-model="text" placeholder=""></b-form-input>

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

