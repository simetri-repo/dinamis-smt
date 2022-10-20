<template>
  <!-- Page Title
  =============================================-->
  <section id="page-title" class="nobg">
    <div class="container clearfix">
      <h1>News</h1>
      <ol class="breadcrumb">
        <li class="breadcrumb-item"><a href="#">Home</a></li>
        <li class="breadcrumb-item" aria-current="page">News</li>
      </ol>
    </div>
  </section>
  <!-- #page-title end -->
  <!-- Content
		============================================= -->
  <section id="content">
    <div class="content-wrap">
      <div class="container clearfix">
        <!-- Post Content
					============================================= -->
        <div class="col-sm-12">
          <div class="row">
            <!--  -->
            <div class="col-sm-8">
              <div class="clearfix">
                <div class="entry-image">
                  <a data-lightbox="image"
                    ><v-lazy-image
                      class="image_fade"
                      src="/src/assets/style/images/blog/workshop.jpg"
                      alt="Standard Post with Image"
                  /></a>
                </div>
                <div class="entry-c">
                  <div class="entry-title">
                    <h4>
                      <a> Simetri Hadir di Electric & Power Indonesia 2019</a>
                    </h4>
                  </div>
                  <ul class="entry-meta clearfix">
                    <li>
                      <i class="icon-calendar3"></i>
                    </li>
                    <li>
                      <a href="#"><i class="icon-folder-open"></i></a>
                    </li>
                  </ul>
                  <div class="entry-content">
                    <p align="justify">
                      <span
                        >Pada tanggal 11 -14 September 2019, Simetri menjadi
                        bagian dari Pameran Electric &amp; Power Indonesia 2019
                        di JIE Kemayoran Electric &amp; Power Indonesia adalah
                        Exhibition terbesar di Asia Tenggara yang ...</span
                      ><br />
                    </p>

                    <router-link
                      :to="{ name: 'simetri.news2' }"
                      class="button button-border button-rounded"
                      >Read More</router-link
                    >
                    <br />
                  </div>
                </div>
              </div>
            </div>

            <div class="col-sm-4">
              <div class="entry">
                <div class="entry-image">
                  <a data-lightbox="image"
                    ><v-lazy-image
                      class="image_fade"
                      src="/src/assets/style/images/blog/new-blog/empowering.jpg"
                      alt="Standard Post with Image"
                      style="height: auto"
                  /></a>
                </div>
                <div class="entry-c">
                  <div class="entry-title">
                    <h5>
                      <a>
                        Kapal Pembangkit Listrik Dikabarkan Meledak di Sulawesi
                      </a>
                    </h5>
                  </div>
                  <div class="entry-content">
                    <router-link
                      :to="{ name: 'simetri.news1' }"
                      class="button button-border button-rounded"
                      >Read More</router-link
                    >
                  </div>
                </div>
              </div>
              <br />
              <hr />
              <!--  -->
              <div class="entry">
                <div class="entry-image">
                  <a data-lightbox="image"
                    ><v-lazy-image
                      class="image_fade"
                      src="/src/assets/style/images/blog/new-blog/empowering.jpg"
                      alt="Standard Post with Image"
                      style="height: auto"
                  /></a>
                  <!-- <br /> -->
                </div>
                <div class="entry-c">
                  <div class="entry-title">
                    <h5>
                      <a> Custom Busbar untuk Panel Listrik Anda </a>
                    </h5>
                  </div>
                  <div class="entry-content">
                    <router-link
                      :to="{ name: 'simetri.news3' }"
                      class="button button-border button-rounded"
                      >Read More</router-link
                    >
                  </div>
                </div>
              </div>
            </div>

            <!--  -->
          </div>
        </div>
        <hr />
        <div class="col-sm-12">
          <div class="row">
            <div class="col-sm-4">
              <div class="entry clearfix">
                <div class="entry-image">
                  <a data-lightbox="image"
                    ><v-lazy-image
                      class="image_fade"
                      src="/src/assets/style/images/blog/new-blog/blog2.png"
                      alt="Standard Post with Image"
                  /></a>
                </div>
                <div class="entry-c">
                  <div class="entry-title">
                    <h4>
                      <a> Perlindungan Maksimal Panel Listrik </a>
                    </h4>
                  </div>
                  <div class="entry-content">
                    <p
                      align="justify"
                    >
Panel listrik berfungsi mengatur energi listrik dari pembangkit listrik ke peralatan elektronik sebuah gedung, pabrik, atau infrastruktur lainnya. Setiap. . .
                    </p>

                    <router-link
                      :to="{ name: 'simetri.news4' }"
                      class="button button-border button-rounded"
                      >Read More</router-link
                    >
                  </div>
                </div>
              </div>
            </div>

            <div class="col-sm-4">
              <div class="entry clearfix">
                <div class="entry-image">
                  <a data-lightbox="image"
                    ><v-lazy-image
                      class="image_fade"
                      src="/src/assets/style/images/blog/new-blog/blog6.png"
                      alt="Standard Post with Image"
                  /></a>
                </div>
                <div class="entry-c">
                  <div class="entry-title">
                    <h4>
                      <a>5 Tipe Panel Listrik dan Fungsi</a>
                    </h4>
                  </div>
                  <div class="entry-content">
                    <p
                      
                      align="justify"
                    >
                      Panel listrik memiliki bermacam-macam tipe sesuai dengan fungsinya. Masing-masing tipe tersebut memiliki karakteristik dan komponen yang berbeda. Penama. . .
                    </p>

                    <router-link
                      :to="{ name: 'simetri.news5' }"
                      class="button button-border button-rounded"
                      >Read More</router-link
                    >
                  </div>
                </div>
              </div>
            </div>

            <div class="col-sm-4">
              <div class="entry clearfix">
                <div class="entry-image">
                  <a data-lightbox="image"
                    ><v-lazy-image
                      class="image_fade"
                      src="/src/assets/style/images/blog/new-blog/blog1.png"
                      alt="Standard Post with Image"
                  /></a>
                </div>
                <div class="entry-c">
                  <div class="entry-title">
                    <h4>
                      <a>Fungsi Ampere Meter</a>
                    </h4>
                  </div>
                  <div class="entry-content">
                    <p
                      align="justify"
                    >
             Amperemeter adalah alat yang digunakan untuk mengukur kuat arus listrik dalam rangkaian tertutup pada panel listrik. Amperemeter digunakan un. . .       </p>

                    <router-link
                      :to="{ name: 'simetri.news6' }"
                      class="button button-border button-rounded"
                      >Read More</router-link
                    >
                  </div>
                </div>
              </div>
            </div>
          </div>
          <!-- #posts end -->
        </div>
        <!-- paging -->
        <div class="col-sm-12 center">
          <button class="btn btn-primary" style="margin-right: 3px" disabled>
            1
          </button>
          <button
            href=""
            class="btn btn-info"
            style="margin-right: 3px"
            disabled
          >
            <i class="fas fa-angle-right"></i>
          </button>
        </div>
        <!-- .postcontent end -->
      </div>
      <!-- .postcontent end -->
    </div>
  </section>
  <!-- #content end -->

  <!-- #content end -->
</template>

<script>
import VLazyImage from "v-lazy-image";
export default {
  components: {
    VLazyImage,
  },
};
</script>
