<!-- Please remove this file from your project -->
<template>
  <div>
    <b-card body-bg-variant="info">
      <b-icon icon="list" align="left"></b-icon>
      <b-container class="bv-example-row">
        <b-row>
          <b-col>
            <div>
              
              <b-button v-b-toggle.sidebar-1 variant="light"> </b-button>
              <b-sidebar id="sidebar-1" title="การจัดการข้อมูล" shadow>
                <div class="px-3 py-2">
                  <b-col>
                    <b-link
                      ><font size="5"> ภาพรวมของฟาร์ม</font></b-link
                    ></b-col
                  >
                  <b-col>
                    <b-link><font size="5"> ข้อมูลทั่วไป</font></b-link></b-col
                  >
                  <b-col>
                    <b-link><font size="5"> ข้อมูลแพะนม</font></b-link></b-col
                  >
                  <b-col>
                    <b-link
                      ><font size="5"> ข้อมูลการผสมพันธ์ุแพะนม</font></b-link
                    ></b-col
                  >
                  <b-col>
                    <b-link
                      ><font size="5"> จัดการข้อมูลยา-วัคซีน</font></b-link
                    ></b-col
                  >
                  <b-col>
                    <b-link
                      ><font size="5"> จัดการข้อมูลน้ำนม</font></b-link
                    ></b-col
                  >
                  <b-col>
                    <b-link
                      ><font size="5"> ข้อมูลการรักษา</font></b-link
                    ></b-col
                  >
                  <b-col>
                    <b-link
                      ><font size="5"> ข้อมูลการรับ-จ่ายยา</font></b-link
                    ></b-col
                  >
                </div>
              </b-sidebar>
            </div>
          </b-col>
          <b-col align="right">
            <b-button variant="success" href="../login">เข้าสู่ระบบ</b-button>
          </b-col>
        </b-row>
      </b-container>
    </b-card>
    <!-- <div
    class="relative flex items-top justify-center min-h-screen bg-gray-100 sm:items-center sm:pt-0"
  >
    <div>
      <b-nav
        variant="info"
        align="center"
        style="background-color: #cc66ff !important"
      >
        <b-nav-item active href="../"
          ><font color="white">หน้าหลัก</font></b-nav-item
        >
        <b-nav-item active href="../table"
          ><font color="white">จัดการข้อมูลแพะ</font></b-nav-item
        >
        <b-nav-item><font color="white">ตั้งค่า</font></b-nav-item>
        <b-button variant="success" href="../login">เข้าสู่ระบบ</b-button>

        <p class="h1 mb-1" align="right">
          <b-icon v-b-toggle.sidebar-right icon="list"></b-icon>
        </p>
        <b-sidebar id="sidebar-right" title="Sidebar" right shadow>
          <div class="px-3 py-2">
            <b-button variant="success" href="../login">เข้าสู่ระบบ</b-button>
          </div>
        </b-sidebar>
      </b-nav>
    </div> -->
    <!-- <b-breadcrumb :items="items"></b-breadcrumb> -->
    <!-- <nav class="navbar navbar-expand-lg bg-light">
      <div class="container-fluid">
        <a class="navbar-brand" href="#">ชื่อฟาร์ม</a>
        <button
          class="navbar-toggler"
          type="button"
          data-bs-toggle="collapse"
          data-bs-target="#navbarSupportedContent"
          aria-controls="navbarSupportedContent"
          aria-expanded="false"
          aria-label="Toggle navigation"
        >
          <span class="navbar-toggler-icon"></span>
        </button>
        <div class="collapse navbar-collapse" id="navbarSupportedContent">
          <ul class="navbar-nav me-auto mb-2 mb-lg-0">
            <li class="nav-item">
              <a class="nav-link active" aria-current="page" href="#"
                >หน้าหลัก</a
              >
            </li>
            <li class="nav-item">
              <a class="nav-link" href="../table">จัดการข้อมูลแพะ</a>
            </li>
            <li class="nav-item">
              <a class="nav-link" href="#">ตั้งค่า</a>
            </li>
            <div class="justify-content-end">
              <button type="button" class="btn btn-success">เข้าสู่ระบบ</button>
            </div>
          </ul>
        </div>
      </div>
    </nav> -->
    <div class="card">
      <div class="card-body">
        <div>
          <b-carousel
            id="carousel-1"
            v-model="slide"
            :interval="4000"
            controls
            indicators
            background="#ababab"
            img-width="960"
            img-height="300"
            style="text-shadow: 1px 1px 2px #333"
            @sliding-start="onSlideStart"
            @sliding-end="onSlideEnd"
          >
            <b-carousel-slide
              img-width="960"
              img-height="300"
              img-src="https://obs.line-scdn.net/0hvx71Y16hKVcKSABOTU9WADAeKjg5JDpUbn54VFYmd2NwfjoEZipnYiZMcWUkLG4JZH5jMi9OMmZ1Kz4HNitn/w1200"
            ></b-carousel-slide>

            <b-carousel-slide
              img-src="https://www.amarinbabyandkids.com/app/uploads/2018/06/Gold-milk-1024x535.jpg"
            >
            </b-carousel-slide>

            <b-carousel-slide
              img-src="https://static.posttoday.com/media/content/2020/09/14/CB75279F5D558B74FE70121EAFC894F6_1000.png"
            ></b-carousel-slide>
          </b-carousel>
        </div>
      </div>
    </div>

    <h3 align="center">แบบบันทึกข้อมูลประจำฟาร์ม</h3>
    <br />
    <br />
    <b-container class="bv-example-row">
      <b-row>
        <b-col>
          <div class="card">
            <div class="card-body">แบบบันทึกข้อมูลทะเบียนประวัติแพะนม</div>
          </div>
        </b-col>
      </b-row>

      <br />
      <br />

      <b-col>
        <div class="card">
          <div class="card-body">
            แบบบันทึกข้อมูลประวัติการให้ผลผลิต (รายฟาร์ม)
          </div>
        </div>
      </b-col>

      <br />
      <br />

      <b-col>
        <div class="card">
          <div class="card-body">
            แบบบันทึกข้อมูลประวัติการให้ผลผลิต (รายตัว)
          </div>
        </div>
      </b-col>

      <br />
      <br />

      <b-col>
        <div class="card">
          <div class="card-body">แบบบันทึกข้อมูลการสืบพันธุ์ของแม่พันธุ์</div>
        </div>
      </b-col>
      <br />
      <br />

      <b-col>
        <div class="card">
          <div class="card-body">
            แบบบันทึกข้อมูลการรับ-จ่ายเวชภัณฑ์และสารเคมี
          </div>
        </div>
      </b-col>

      <br />
      <br />

      <b-col>
        <div class="card">
          <div class="card-body">
            แบบบันทึกข้อมูลการใช้วัคซีน และการถ่ายพยาธิ (ทั้งฝูง)
          </div>
        </div>
      </b-col>

      <br />
      <br />

      <b-col>
        <div class="card">
          <div class="card-body">แบบบันทึกข้อมูลการรักษาโรค</div>
        </div>
      </b-col>

      <br />
      <br />

      <b-col>
        <div class="card">
          <div class="card-body">การบันทึกข้อมูลบัญชีฟาร์ม</div>
        </div>
      </b-col>

      <br />
      <br />

      <b-col>
        <div class="card">
          <div class="card-body">แบบบันทึกประวัติบุคลากร</div>
        </div>
      </b-col>
    </b-container>
  </div>
</template>

<script>
export default {
  name: "home",
  data() {
    return {
      slide: 0,
      sliding: 4,
      //  items: [
      //       {
      //         text: 'หน้าหลัก',
      //         href: '../'
      //       },
      //       {
      //         text: 'จัดการข้ามูลแพะ',
      //         href: '../table'
      //       },
      //       {
      //         text: 'ตั้งค่า',
      //         href: ''
      //       }
      //     ]
    };
  },
  methods: {
    prev() {
      this.$refs.myCarousel.prev();
    },
    next() {
      this.$refs.myCarousel.next();
    },
  },
};
</script>
