<!-- template-->
<template>
  <div>
    <!--app par-->
    <v-card class="overflow-hidden">
    <v-app-bar
      absolute
      color="blue-grey lighten-3"
    >
      <v-app-bar-nav-icon></v-app-bar-nav-icon>

      <v-spacer></v-spacer>
      <v-img
        max-height="60"
        max-width="210"
        src="@/assets/logo .png"
></v-img>
    </v-app-bar>
    <v-sheet
      id="scrolling-techniques-7"
      class="overflow-y-auto"
      max-height="56"
    >
      <v-container style="height: 1500px;">
      </v-container>
    </v-sheet>
  </v-card>
    <!-- end app par-->

    <!--welcome img-->
    <v-carousel
      cycle
      height="700"
      hide-delimiter-background
      show-arrows-on-hover
    >
      <v-carousel-item
        v-for="(slide, i) in slides"
        :key="i"
      >
        <v-sheet
          :color="colors[i]"
          height="100%"
        >
        </v-sheet>
      </v-carousel-item>
      <v-carousel-item
        v-for="(item,i) in items"
        :key="i"
        :src="item.src"
      ></v-carousel-item>
    </v-carousel>
    <!--end welcome img-->

    <!--all card-->
    <v-row>
      <!--1 col-->
      <v-col cols="4">
        <!--1 card-->
        <v-card
          class="mx-auto"
          max-width="400"
        >
          <v-img
            class="white--text align-end"
            height="200px"
            :src="require('@/assets/موقع الوزاره.jpg')"
          >
            <v-card-title></v-card-title>
          </v-img>

          <v-card-subtitle class="pb-0">موقع وزارة التربية والتعليم</v-card-subtitle>

          <v-card-text class="text--primary">
            <div>Whitehaven Beach</div>
            <div>Whitsunday Island, Whitsunday Islands</div>
          </v-card-text>

          <v-card-actions>

            <v-btn
              color="orange"
              text
              href="http://portal.moe.gov.eg/Pages/moe-homepage.aspx"
              target="blank"
            >
              GO
            </v-btn>

            <v-btn
              color="orange"
              text
            >
              Explore
            </v-btn>
          </v-card-actions>

        </v-card>
        <!--end 1 card-->
      </v-col>
      <!--end 1 col-->

      <!--2 col-->
      <v-col cols="4">
        <!--2 card-->
        <v-card
          class="mx-auto"
          max-width="400"
        >
          <v-img
            class="white--text align-end"
            height="200px"
            :src="require('@/assets/نتيجه الثانوي.jpg')"
            aspect-ratio=""
          >
            <v-card-title></v-card-title>
          </v-img>

          <v-card-subtitle class="pb-0">نتيجة الثانوية العامة 2020</v-card-subtitle>

          <v-card-text class="text--primary">
            <div>Whitehaven Beach</div>
            <div>Whitsunday Island, Whitsunday Islands</div>
          </v-card-text>

          <v-card-actions>

            <v-btn
              color="orange"
              text
              href="https://g12.emis.gov.eg/"
              target="blank"
            >
              GO
            </v-btn>

            <v-btn
              color="orange"
              text
            >
              Explore
            </v-btn>
          </v-card-actions>

        </v-card>
        <!--end 2 card-->
      </v-col>
      <!--end 2 col-->

      <!--3 col-->
      <v-col cols="4">
      <!--end name project-->
      <!--3 card-->
        <v-card
        class="mx-auto"
        max-width="400"
      >
        <v-img
          class="white--text align-end"
          height="200px"
            :src="require('@/assets/Information center.jpeg')"
        >
          <v-card-title></v-card-title>
        </v-img>

        <v-card-subtitle class="pb-0">مركز المعلومات </v-card-subtitle>

        <v-card-text class="text--primary">
          <div>Whitehaven Beach</div>

          <div>Whitsunday Island, Whitsunday Islands</div>
        </v-card-text>

        <v-card-actions>
          <v-btn
            color="orange"
            text
            href="http://emis.gov.eg/"
            target="blank"
          >
            GO
          </v-btn>

          <v-btn
            color="orange"
            text
          >
            Explore
          </v-btn>
        </v-card-actions>
        </v-card>
      <!--end 3 card-->
      </v-col>
      <!--end 3 col-->   

      <!--4 col-->
      <v-col cols="4">
      <!--end name project-->
      <!--4 card-->
        <v-card
        class="mx-auto"
        max-width="400"
      >
        <v-img
          class="white--text align-end"
          height="200px"
            :src="require('@/assets/وزارة التربية والتعليم مصر.jpg')"
        >
          <v-card-title>Top 10 Australian beaches</v-card-title>
        </v-img>

        <v-card-subtitle class="pb-0">Number 10</v-card-subtitle>

        <v-card-text class="text--primary">
          <div>Whitehaven Beach</div>

          <div>Whitsunday Island, Whitsunday Islands</div>
        </v-card-text>

        <v-card-actions>
          <v-btn
            color="orange"
            text
            href=""
            target="blank"
          >
            GO
          </v-btn>

          <v-btn
            color="orange"
            text
          >
            Explore
          </v-btn>
        </v-card-actions>
        </v-card>
      <!--end 4 card-->
      </v-col>
      <!--end 4 col-->   

      <!--5 col-->
      <v-col cols="4">
      <!--end name project-->
      <!--5 card-->
        <v-card
        class="mx-auto"
        max-width="400"
      >
        <v-img
          class="white--text align-end"
          height="200px"
            :src="require('@/assets/وزارة التربية والتعليم مصر.jpg')"
        >
          <v-card-title></v-card-title>
        </v-img>

        <v-card-subtitle class="pb-0"> وزارة التربية والتعليم من 2020/2014</v-card-subtitle>

        <v-card-text class="text--primary">
          <div>Whitehaven Beach</div>

          <div>Whitsunday Island, Whitsunday Islands</div>
        </v-card-text>

        <v-card-actions>
          <v-btn
            color="orange"
            text
            href="http://moe.gov.eg/adv/Harvest_of_the_Ministry_of_Education_from_2014_to_2020.pdf"
            target="blank"
          >
            GO
          </v-btn>

          <v-btn
            color="orange"
            text
          >
            Explore
          </v-btn>
        </v-card-actions>
        </v-card>
      <!--end 5 card-->
      </v-col>
      <!--end 5 col-->   

      <!--6 col-->
      <v-col cols="4">
      <!--end name project-->
      <!--6 card-->
        <v-card
        class="mx-auto"
        max-width="400"
      >
        <v-img
          class="white--text align-end"
          height="200px"
            :src="require('@/assets/بنك-المعرفة-المصري-3.jpg')"
        >
          <v-card-title></v-card-title>
        </v-img>

        <v-card-subtitle class="pb-0">بنك-المعرفة</v-card-subtitle>

        <v-card-text class="text--primary">
          <div>Whitehaven Beach</div>

          <div>Whitsunday Island, Whitsunday Islands</div>
        </v-card-text>

        <v-card-actions>
          <v-btn
            color="orange"
            text
            href="https://www.ekb.eg/"
            target="blank"
          >
            GO
          </v-btn>

          <v-btn
            color="orange"
            text
          >
            Explore
          </v-btn>
        </v-card-actions>
        </v-card>
      <!--end 6 card-->
      </v-col>
      <!--end 6 col-->   

      <!--7 col-->
      <v-col cols="3">
      <!--end name project-->
      <!--7 card-->
        <v-card
        class="mx-auto"
        max-width="400"
      >
        <v-img
          class="white--text align-end"
          height="200px"
            :src="require('@/assets/covid19.jpg')"
        >
          <v-card-title></v-card-title>
        </v-img>

        <v-card-subtitle class="pb-0">عراض فيروس كورونا المستجدة وطرق الوقاية من منه</v-card-subtitle>

        <v-card-text class="text--primary">
          <div>Whitehaven Beach</div>

          <div>Whitsunday Island, Whitsunday Islands</div>
        </v-card-text>

        <v-card-actions>
          <v-btn
            color="orange"
            text
            href="http://moe.gov.eg/adv/Corona_Virus_Poster.pdf"
            target="blank"
          >
            GO
          </v-btn>

          <v-btn
            color="orange"
            text
          >
            Explore
          </v-btn>
        </v-card-actions>
        </v-card>
      <!--end 7 card-->
      </v-col>
      <!--end 7 col-->   

      <!--8 col-->
      <v-col cols="3">
      <!--end name project-->
      <!--8 card-->
        <v-card
        class="mx-auto"
        max-width="400"
      >
        <v-img
          class="white--text align-end"
          height="200px"
            :src="require('@/assets/وزارة التربية والتعليم مصر.jpg')"
        >
          <v-card-title></v-card-title>
        </v-img>

        <v-card-subtitle class="pb-0">Namber 10</v-card-subtitle>

        <v-card-text class="text--primary">
          <div>Whitehaven Beach</div>

          <div>Whitsunday Island, Whitsunday Islands</div>
        </v-card-text>

        <v-card-actions>
          <v-btn
            color="orange"
            text
          >
            GO
          </v-btn>

          <v-btn
            color="orange"
            text
          >
            Explore
          </v-btn>
        </v-card-actions>
        </v-card>
      <!--end 8 card-->
      </v-col>
      <!--end 8 col-->   

      <!--9 col-->
      <v-col cols="3">
      <!--end name project-->
      <!--9 card-->
        <v-card
        class="mx-auto"
        max-width="400"
      >
        <v-img
          class="white--text align-end"
          height="200px"
            :src="require('@/assets/وزارة التربية والتعليم مصر.jpg')"
        >
          <v-card-title>Top 10 Australian beaches</v-card-title>
        </v-img>

        <v-card-subtitle class="pb-0">Number 10</v-card-subtitle>

        <v-card-text class="text--primary">
          <div>Whitehaven Beach</div>

          <div>Whitsunday Island, Whitsunday Islands</div>
        </v-card-text>

        <v-card-actions>
          <v-btn
            color="orange"
            text
          >
            GO
          </v-btn>

          <v-btn
            color="orange"
            text
          >
            Explore
          </v-btn>
        </v-card-actions>
        </v-card>
      <!--end 9 card-->
      </v-col>
      <!--end 9 col-->   

      <!--10 col-->
      <v-col cols="3">
      <!--end name project-->
      <!--10 card-->
        <v-card
        class="mx-auto"
        max-width="400"
      >
        <v-img
          class="white--text align-end"
          height="200px"
          :src="require('@/assets/وزارة التربية والتعليم مصر.jpg')"
        >
          <v-card-title>Top 10 Australian beaches</v-card-title>
        </v-img>

        <v-card-subtitle class="pb-0">Number 10</v-card-subtitle>

        <v-card-text class="text--primary">
          <div>Whitehaven Beach</div>

          <div>Whitsunday Island, Whitsunday Islands</div>
        </v-card-text>

        <v-card-actions>
          <v-btn
            color="orange"
            text
          >
            GO
          </v-btn>

          <v-btn
            color="orange"
            text
          >
            Explore
          </v-btn>
        </v-card-actions>
        </v-card>
      <!--end 10 card-->
      </v-col>
      <!--end 10 col-->     
    </v-row>
    <!--end all card-->

  <v-row>
    <v-col cols="7">
      <v-card
    class="mx-8"
    max-width="500"
  >

    <v-toolbar
      color="blue darken-1"
      dark
    >

      <v-toolbar-title>Discover</v-toolbar-title>
      
    </v-toolbar>

    <v-container fluid>
      <v-row dense>
        <v-col
          v-for="card in cards"
          :key="card.title"
          :cols="card.flex"
        >
          <v-card>
            <v-img
              :src="card.src"
              class="white--text align-end"
              gradient="to bottom, rgba(0,0,0,.1), rgba(0,0,0,.5)"
              height="200px"
            >
              <v-card-title v-text="card.title"></v-card-title>
            </v-img>

            <v-card-actions>
              <v-btn icon
              :href="card.link"
              target="blank"
              >
                <v-icon>mdi-account-search</v-icon>
              </v-btn>
            </v-card-actions>
          </v-card>
        </v-col>
      </v-row>
    </v-container>
  </v-card>
    </v-col>
    <v-col cols="5">
      <v-img 
      width="600" 
      src="@/assets/وزارة التربية والتعليم مصر.jpg"/>
    </v-col>
  </v-row>

  <!-- <div class="player-container">
    <vue-core-video-player 
      src="./videos/your_video.mp4"
      >
      </vue-core-video-player>
  </div> -->

  <!-- <youtube 
  video-id="-SEKZygCLmM" 
  ref="youtube" 
  >
  </youtube> -->

      <v-parallax
      dark
      height="300"
      src="https://cdn.vuetifyjs.com/images/backgrounds/vbanner.jpg"
    >
      <v-row
        align="center"
        justify="center"
      >
        <v-col
          class="text-center"
          cols="12"
        >
          <h1 class="subheading">
            موقع : وزارة التربيبة و التعليم و التعليم الفني
          </h1>
        </v-col>
      </v-row>
    </v-parallax>

      <!-- footer -->
      <v-footer
        dark
        padless
      >
        <v-card
          flat
          tile
          class="blue darken-1 white--text text-center"
        >
          <v-card-text>
            <v-btn
              v-for="(object, A) in icons"
              :key="A"
              :href="object.link"
              class="mx-4"
              color="black"
              dark
              fab
              target="blank"
            >
              <v-icon size="24px">
                {{ object.icon}}
              </v-icon>
            </v-btn>
          </v-card-text>

          <v-card-text class="white--text pt-0">
            Phasellus feugiat arcu sapien, et iaculis ipsum elementum sit amet. Mauris cursus commodo interdum. Praesent ut risus eget metus luctus accumsan id ultrices nunc. Sed at orci sed massa consectetur dignissim a sit amet dui. Duis commodo vitae velit et faucibus. Morbi vehicula lacinia malesuada. Nulla placerat augue vel ipsum ultrices, cursus iaculis dui sollicitudin. Vestibulum eu ipsum vel diam elementum tempor vel ut orci. Orci varius natoque penatibus et magnis dis parturient montes, nascetur ridiculus mus.
          </v-card-text>

          <v-divider></v-divider>
          
          <v-card-text class="white--text">
            <strong>Copyright © {{ new Date().getFullYear() }}  Abdelrahman-BE. All rights reserved</strong>
          </v-card-text>
        </v-card>
      </v-footer>
      <!-- footer -->
  </div>
</template>
<!--end template-->
<!--script-->
<script>
  export default {
    data () {
      return {
        items: [
          {
            src: 'https://www.alsbbora.info/upload/photo/news/8/4/600x338o/401.jpg?q=2',
          },
          {
            src: 'https://imgy.pro/veto/492x307/720202412431575510545.jpg',
          },
          {
            src: 'https://alborsaanews.com/app/uploads/2017/02/1487082108_825_45591_.jpg',
          },
          {
            src: 'https://www.albawabhnews.com/upload/photo/news/378/8/600x338o/918.jpg?q=1',
          },
        ],
        cards: [
          {
            title: 'STEM schools',
            src: 'data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAARMAAAC3CAMAAAAGjUrGAAABg1BMVEX////ogSUAAACvr695eXno6Oj8/Pz12cT4+Pjt7e3u7u7qgiXy8vL0vpf29vbz8/PlegTkfRQbKzOeoqT659bBbiHthCbsoWXrnF1ElLmCQgA+IwjnfhzsqHXb29vlgRHOcxw/Pz9iYmLOzs70y62bm5tClLREREQlJSXkcwDCwsL22MDT09MVFRU3NzcARmKMjIxSUlLwtYjpnFTniDT87uNWIwDpkknM1tyDg4Pwsn4sLzBcXFwLCwu6urpub27Gz9XzxJ8AABHmvp/89OtwYlnnhzBiNhEoEwAhHBRnUTt9YU1QPSrIrZfvl04zCgAJHSaQWB7Pjlizp51BNy7Zv6epjXUXAABJIgDIkmd9qr9fp8QtgaG81+SkxtgweZU5YXpfiZbS6PEAIzXSgTh0ss95o7AQhLCYv9aqg1zgp3jQcAAYUW52jqGSwNuPhnp5TiwAGCoAM0FIUljCbiKbUgBmLACHRQB4RBE+IBFDFAAcAABCKw1lOBgoAABYMxPQw7l65XdLAAAU5klEQVR4nO1ci1/bRrYeyUjWC0vCxrKD7Bj8ANtAY2OtN+ZVEl1DbnfZkG2bbimkpeUmm2bTbhYaunvvzf7pOzN6jR42htgku+jLL8Z6WZpP5zVnzgwAMWLEiBEjRowYMWLEiBEjRowYMWLEiBEjRowYMWLEiBEjxpXAytyHfoSPDRwj8fyHfoiPDAyUEob90E/xcQHxwcfa44PEszLzoR/iY4PMCB9GdZhEupH6IHceBlaSPpQlYdKLj/77s99tJj7Q/QeBZSSJgW8qJdywpEBClj77fXd/v/PFH6o3eudLwacQL1B5OPkGPY+QmKenymxFFSldF6cfFy+7wNzRNG3HuIlng68Lf7CID0m6mVumEov0dhl+qfRFvbOv652D+8OvYNuqquu6ovZu5LXxMgrZwI1xIida9ELD+p5RdS1dfVIq/XGdKZII+EB2TaEwRGXfvIFnZBlBgCGbzLOpyeuOsLWwueD5GU3Xp2foz+fmVunFeQLrS/4n6amUA6Uw6WdEYFMpjmMhKZMO2qStjZWFLYHYk1Gozhdf7GezX075zmRWfZxkFMqDkpzsU9pIMQJzLbUxmiNLFre1QG9sBe6S6SmirlJ64emyb3+Ak7ZKcKJPXlA4CWD7eh29MfV6b7QzGwt0KyGH91fWoOXUc1/5xSTISQeJB6VTKvxHif1JazjqELOoRyxcI5jMKPr+5WexjW16MTHg581Cr/cnOuh1ApzchdJhsL16gTUgO+qkrSzHpHhwXTkB7X7m0htUN1cTXx8C9mTADczqg0ZwX4ATKBxds51ZS06bXfh94p4A+htIDH89e5LRiO+VqPdXXtr+5vXJYf7o6Plx9P0X5sOJmwAnOZ3Spw0zYxo70PisXedJrwpZQH5ndLBNRzoITgy1roVPbdBbIF+r5eH/2hE4Cp9QXrkXcQdm1bdZgX5H0ZL1ZgF92bnCo14XEs9dLU3QVhSbFIITaFu6oTOL9LPDfP4QcpJHf8OiUqUDelOsItzfxH+qthHiOlBQCpCTnk5R/ZsI2mBYEmFMUpI0KFzRFCdGIHWnQoUfdnXrKF87Aexh/gSkTp8fBg5zrUUhsCuxnoZcpNOYEtrRqqQqOpzcUHgiSCEvKTGCLPNMNCuGpuUsEklOjLCeb31/gtgA4KiGNk9rR8fkL5bpsN4kpsBvHYAl19LsKDYnyvRobXofLN+DuH/vnj+DwfO4zdxAy9tew0Lhs7FhTlrP8jVsQyxOUvnac8KkVOly+IcTU/wnNr4FS65Os10Vc6J2bqAPWJ3HUjo1T+7kHYlmB5OSQ298uJywNBQT/ANHebzjMO/JidBqRQ0U+DhZ9+xcRcGc1G/CwKZpfN8FkhPBe1h2gPpAo1IBfk56oZh7eZ2r5ZFZZb/+DmnQST5/5PxcmY5OI0Hd+dTGbwk5AaYlJ8qNJFBaOJuzSOR0fF5ooEtqBzhp50JS3fi+htzw4WH+B+W7Q/gHuR/rrHv0cvBsC4lt0GyaJ0c8f3RCcgI6yBf3+iO16X0R5sQvGoKnPex0wXMtAU56ufBPN74/haQcHx2dPqn/z/HRMXLHrxEn/GJrkPglpox6PXn4/MXx87yPEw3HJzcSr4U5kf1qznp+ulJXvC6fn5OeFmH7io+gBUFG1fjhz9gOIL8MUCA3OP3qyMlJUE5evkz++MXLG0mehDkJxiqSG0JkFCKG9HHSjpASCPpFvoYYbn9Zy6JfPaydQlLuL0X4GweJKe709OTF6dHR1y98nPzlk1cQ343WqPdEkJNU0BuQgkKYVJKTKMVB2H6Vz7+G9rHz6WGhgmxsLX/Cz29E5AxcJKZkKE2n+ePj/KGfE0TJq7+M1qj3RJCTsKPxLEqSyJYQnJBSkiHDzCKdeg0dz077uGZ0gFCryakGnR76OFB3Tk444UQyDePDcMJJQqshyazHSYSfYd1dRj/JSjzP8BJLcJKx+jlcEmJH8UUQU1Ova89fdMr5/LH2+xoUgPublwxaQDl5/vzo8Pnr6XonrDufTFx3WIaR2dYyJ/HMvPOoQoRgO6LDppJUMpXiWE5iZIITS4EydzWtsKYobeJKbvXV6euf/vwc0vHdD4fH3zxYuCzlm5hij49Pjo5PppWujxOe+fSTT5lJ14OwaPTP0h12scxbA6RRqSUZW1mOZwQ2k7V7xNLLECdIg9h2wdcT5FenUp3vUKYg/yTZoC8fA0WcvOCPXhwFOYGWbj3YYRw/0MAO4Kz7traAzODsUsSJSHkgI7jjnhFtgxGWk8jYITX18+zX4DTPnWzPzl862Ic4kaJ1B3Ey+aohfMP0Av7eQEmcFCPwkT6BgXw5Qp/pW6SMyAkMQL/cXJr56zq98cOleUqAY3uOA6x1Nz8n8uQ54bAk0va7W8S5HTmyzwftDmEGKlbc1H4IRuIkuQ85LZeLLGhG5OFC2KIXPdA3rTsyan51Gw+IMqCMs32wHxz2xRLcSWw2LYc8KiddTzr6I3TghDIJ17glK81m5Wf0MYqwXRuIC5beTtB0o4X+IEFJCdCi+Esu8DZpea/GSZJISFauH5nnFEVRs/DD59bGDiQn6Tev3nzz7Ptva6/efIsEBXtimSHGYiy5IUdNh3LCBt2W1vS+sxHZyRGh6fYooDpRTjgecI++qdVqVlo9/9eG64ndyNXJKZEFB0M5Mf2u2InnbOxcs0GG4XKiT5QT6GHTb1BKA3OSzz/73I5YMztat9Pp97trvYe2BeCwxWdRpJqc1vAfrQ0/KmvOB/zTRR9qzj0Rn9VzvyabyabYRH8RbUaSQDNCfkx4qn33iqJ7o8UT5QTw0qNv8gQebwEBJDWos7ouQqAaGKVTYS3+ltPARPqsqLr1R0Wfuvth76fUHAtMaw/adL9Zm+ijjszkdJ3YXY9o6E5dqVesr31iBD178HiJwCWlPFeGXH1DUpJ/1uKaXeKV2KUNFHoyBjAraSBSl0NUNZbtuFuBg/gXMScqtA0qqhdABUjdcPS8D0+0OclZDyWiT/0lWbpjR1djBOSkRuDZ7wpKNgJKzgQyCg+qfWoE9BXN7ASZJaFanOjdZmZaV9aambauhDyseVfvdG1OTE3ripTaLaChL59INcbMCTc/T9MPHj+A/2mEBw/or+Yi8evnf5tfXGyt0ufZUUiB6tMZetiWE2i3mpmeOa1lpsOjNpW6xgJPegq6jnSyI06WE7C8vlVsrBSL1QUsh8tnZ2ezg/DPcpFZWCqNRImoNjvDtMziRNEy0BBVANTWrqGEhlU1/3ifpmNFaivqZDkB88uAX4HhtFUQo6kigWyW3NI1GVSXpJHERFST7Ai6o6yZfaVrGBUYhiWVoPKYlIo4cAWloKvTmJoJc8LOL7MeJ0miZkxHRk0kza3SbCxxLCrHdOGRYJkd0d6rJ/GYt3NQD8G2sfqOmTQLStPImF09WCzQVKh+M4NOhCcNbsIEOCkKjMuJ5jVSyVUyhplpal4ZmZ7jGdbMkXDUQyzt/gbhAO/VkcwTnHRyIazZ9gQazb5KKWtaH57d8T9bQYfvBPlio6/cHdjFKa5GFWq8FyerjFTEnHA8w/RdE+C9s4rHk5qReIbnpRQWZ4EDBjof/y/NlJdhfw13sM0sMgMeJ+qgIW/ki0XPxVL+AT4TPw1Snx1l4G9w95a2xsEDCcgJWF6R+fQ2x7EZVyZUIhE97SqUFSuwKcgMI6VgvGsgfbHkhCgqMrFlHJETEn7laSrWPtOsQEna4cwo/blPT409oQJ1h19eYS3daXqtJ0TV9JTHY4qVGYZPFZH/PrM4CaYXrsGJv6CnYF3vWC1djexRM/fojSFDRdeAzKwWgWtPKp6ckO+kC2NNbFlVIiEk8yAlFKlSqYSUJ4IT9uqcUCqhPGYwOBxUE8u26I2xFV+wAiOkoO4wmylhFY1ne25HIXr3YKeHUegVvMZZg2AGpESkouVEcI3T5Zz07farFe+gI7TOsQGc8NWlhQFD8VcHZESCUeI86sWkGjQavvXsCdUNK29KSHk5FR4nDor/2Htn25P1ICdpN+AdgRNHT4iBs569S+sO46RM0+OzsXbW1eIEauU2yrh5oSeMK0OXSF6i1k7tG7A5tpz8V1B8024v4HJOdFsoRNF7FbaYKRXnoaLlhKkuzY+JFd7OHCG/AzmRrVQ9UdOuqu2QqHh1OnbCFumOrWyV4MnpX+iD7IicKEZHDPxMpm4dEo3hugNRXqWvVrMZDfeN25wAK9VokEZPVbTA7AKOsZPmvH158enmXHaQnLzt26TAUJz1wz6F4GTa0RTncvv16AXX7Q3mJKom7srgXSVAnKDY3i4cmCYnhFB6/W4vSbSV460LU85rQfFJf5A9uZMtPbUl5a4fTmzmcZIxnBs7wmkrjNI03YzjAE6W6RGG0S4FUUqBOEFxrLVPkArBkEHptN1YheOxPHmFF8b5+SxlcxKcXwA5yZYeHUR1GcOcJIGjPLbDs2friH3Tld1BnIynv0OMSiBOVvGUCEECEg9YLRgzUKquZVxOEB9eSp/Z3b1w/E5QpSEncPfTKFLCnDSd707Dvc3MjXDCEo+POKHpDdxAAe1n2vVQH19VNSzSaD4LtCneSJxhh/aDOKGyJTqClDAnFW8al6U8dsAHyUreCCcc0UNAvrhYtWoGkPhAvpJ9JdgIGFhXbE4AOR5ovD04d2K2SE4gICnB5FIUJ2zXZQF4kVLfRIGkiH8BchKy0mPjJCgnNrCc4GM7fSWUI0OVfSE5Ye5cHAyVEyQpYZsS5mQHd349abCPoC4ODF0OfqWDIAo2xm9P5p222PYEb5qViNx9L2xPiH7xIE7gob232UBCKciJuuOJBp6ttE+5QlNRdudmSzZbzoNP3S83bJSrY+GErPR05AT7HV4A9iab6fUDtCg7bNDvQBu7u1uiBvkd67psae+OP6HkTA/2OEHJxH1beZJenIT4qbydQ0k8USTtyf35BQ/jmdPvxSdpetviwGonWT1gNguqP1zJCMH45BzC4iTUB3Q5odSXM9GP7cX2KAnhKE/Pmr/k6NFDunQwt7d3cLb3aH19tQym1iFGKHa6Mtw4tkXT+AXb+sAyPhUwKxRhWfRCMI5FumPb2JkhnExzK5GkTPtcSsaSE5HC89wc1QH3L/Z2Z0sXBwcXTxhhaRnMNxiISawM4vR3llu4A+XVBAdr2Sp9Ivfo9gvt/k5xz+4XU8rD4B1ITgC3FJU09TjBIf2azUTGdFQHoLqyzQPIPOTkLSQOdmwmWKjkq0bC3dwUNllbCWS3iBMNL9fs9dCcfvHs2Vmw8+bAxwmQojLJHid4Nu6OHae1bdXBCdAyjVjPvpu9OEecpNilCa6nYOVPLGBRLNK/cfAzKSxJlxNiXMXSHoNyRoMv4ySSFC/PhpOOjmXtap61BfyfUNYqu1fahZxwNJCWJrqgDsqz4cZbfqj4d3d02D+RquuYFK/Xatvk4j+ezmVH4ySKFE9OrFEMy/OIzqB7B7snDW/R1LvZAs70hDqb44bMIGGxbAjkxHltoi+hlHN7pkQazM7HUv2gWjkIcgK49SApLifIrgLX3Th3s6Qyh76f7UFJKYDyYnDW8USAEvAMHrAp/t0b3fG1sBvBiXWZcRVOAFgPVIp4uqPibbNOcmKPHaDUo3i+m30KOdnaBsXWGBs/ECyT4tHAxPL/uplysUPk2DLem8NRkz2+g5YtK9L0yLoDUBWDnxSCE+vlrxFRolOPgjjJvjunaHj39D1Q3pgEB0GgtZQAy8nlRW9oVM+52mPmPBs7LUM2GF5m7euMrNPukTgBXMunPkE58SmPY9ARJ6XNUmkTdn6qaVAeexVBBNweYbGVVL0cNdVuGgZvZB4S5QFqMkXM34cXGrOzZ5dzAh2Jg9wfPstZXxDnIU5MInnjDLt1Ua3WbvZsDsrJVAI0tifMBwLv+DaoqWRCSYcE9fsqWVoXWNOD54pzc7uX6w5ZV0DNXWTdbmCIE2IQ3y3lgpyU6FL2/P/uFsBGw5ITqTGOdONAeIkDyIl5l8wRiIHER7DdHIP7xeIATt66B32ApIh2SIw5werncOIpjxsLdcXs7gUKZKGczJctG5u4ZFLUe8KrekV3y3jaI1JnF7Nkk9RCcG4CX4RdwIPSAE7+3+k0+yBSv+7CD4+TgwOCE9OVLdXJAnf18z3I3NwstCfry0DYZFAvbWxDf1Hw+jfFRYBmXHi6Mkc/JaUkF5rqxC1fwGbj6D5qfGd29nwzqtLrqwtRdDjJntNobMzhxBk4d6I4gHSHRnegkddbhJ2O9Mr2fGuSAT6Zh1zAo4ym5liQ7AX9zpMTpcAKoQgyM0x37sBDc6Ww8ojUu12XE/GMpqE0upw4o8Ser9qHsQklzu5lISf3UPe6uFVMTNT5eO9eoq1USiqJcmwowO7vOW9ZVzrNqOlfRkT30AG0J1BPSr6SOLtMDpLi2tjswQFsssuJ2UcXkMUe+3cuslR29wBxwtC4/86PZURnIIh2Vq3Zo5wAkoW7dRX6iEclVEitKvW1CutP49rIeFXQoXUV0r+USqW92VIk9n5x66jfvlWU0o+Mgyfw6I9KqcQw9tvq/Eifl97S8EwNpcASxeKELWxEO+16+0qh+8Neqd/pam27Ep4LJy5SX7jV8qEh98TjmZmZ9ZlorON8Cq63/+mnZHJjZsUBPPj4p+bG4xWn4cnmP/82s43ORDQWt5dWFiYqJVHtdESHl2VrTlXUvAwbEZReGdWPbIlUa55XAO78HXndPiqE5u84GMPikB8dJ1GLgKJ5XniNHNn1eKF5Xg7+EzmJkhM0HxDH+zIRBQTmAzr4T+SEi5iF6WZqZd+YjRCVGx5Dvjj9sXECQi+fmF8sLaUTHtLpKrlpoRrac2WMachqjPDPr2Ylch46d2+KwDb+2J4K7XtfjLe6dQxgvdEjNsXbOesoK8Fa58nkInbcsEVM/o2B1rXgWA7lE91MytB1LSSUaOPwuhY3tJr3BwBa5oMXZCKDNnT9Eysha61/cpswbJ2c24ph6yndWgxed+v2YvD6bLcYA9fxu8UYbb3HW4aR1gW9bRhh/djbh0vXGb6NGLoe9W0FO2Td8hgxYsSIESNGjBgxYsSIESNGjBgxYsSIESNGjBgxYsSIESNGjBgxYsSIESNGjBgxYsSIESNGjBgxYsTA+BeYxZtinFyslQAAAABJRU5ErkJggg==',
            flex: 12,
            link: 'http://moe.gov.eg/stem/index.html',
          },
          { 
            title: 'Japanese schools',
            src: 'https://www.elmashhad.online/files/2018/7/2/457bd068a0187f055fbac0fba7be9729.jpeg',
            flex: 6,
            link: 'https://ejs.moe.gov.eg/'
          },
          { 
            title: 'Best airlines',
            src: 'https://cdn.vuetifyjs.com/images/cards/plane.jpg',
            flex: 6,
            link: ''
          },
        ],
        dialog: false,
        icons: [
          {
            icon: 'mdi-facebook',
            link: 'https://www.facebook.com/egypt.moe/',
          },
          {
            icon: 'mdi-youtube',
            link: 'https://www.youtube.com/channel/UCx_uN4itkgf_aymy5xbdmXQ',
          },
          {
            icon: 'mdi-twitter',
            link: ''
          },
          {
            icon: 'mdi-linkedin',
            link: ''
          },
          {
            icon: 'mdi-instagram',
            link: ''
          },
      ],
      }
    },
    methods: {
      showAlert() {
        alert("boody")
      }
    }
  }
</script>
<!--end script-->