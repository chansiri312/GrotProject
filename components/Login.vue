<!-- <template>
    <b-container fluid>
      <b-row class="my-1" v-for="type in types" :key="type">
        <b-col sm="3">
          <label :for="`type-${type}`">Type <code>{{ type }}</code>:</label>
        </b-col>
        <b-col sm="9">
          <b-form-input :id="`type-${type}`" :type="type"></b-form-input>
        </b-col>
      </b-row>
    </b-container>
  </template> -->
<template>
  <b-container fluid>
    <br />
    <br />
    <h3 align="center">เข้าสู่บัญชีของคุณ</h3>

    <b-row class="my-1">
      <b-col sm="2">
        <label for="input-small">Username:</label>
      </b-col>
      <b-col sm="10">
        <b-form-input
          id="input-small"
          size="sm"
          placeholder="Enter your name"
        ></b-form-input>
      </b-col>
      <br />
      <br />
      <b-col sm="2">
        <label for="input-small">Password:</label>
      </b-col>
      <b-col sm="10">
        <b-form-input
          id="input-small"
          size="sm"
          placeholder="Enter your password"
        ></b-form-input>
      </b-col>
    </b-row>
    <br />
    <br />
    <div align="center">
      <b-button variant="success" style="width:200px; height:100; ">เข้าสู่ระบบ</b-button>
    </div>
    <div  align="center">
      <b-button variant="white" style="width:200px; height:100; ">ลืมรหัสผ่าน</b-button>
    </div>
    <br />
    <br />
    <div align="center">
      <p>ยังไม่มีบัญชีใช่หรือไม่?</p>
    </div>
    <div  align="center">
      <b-button variant="white" style="width:200px; height:100; " href="../Register"><font color = "success">สร้างบัญชีใหม่</font></b-button>
    </div>

    
  </b-container>
</template>

<!-- <script>

    export default {
        name: 'login',
      data() {
        return {
          types: [
            'text',
            'number',
            'email',
            'password',
            'search',
            'url',
            'tel',
            'date',
            'time',
            'range'
            
          ]
        }
      }
    }
  </script> -->
