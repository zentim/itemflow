<template>
  <v-container fluid>
    <section>

        <v-layout column align-center justify-center>
          <div class="headline mb-3 text-xs-center">Note-taking Application</div>
          <em>Kick-start your note today</em>
          <v-layout>
            <v-btn
              class="my-5"
              dark
              large
              color="blue darken-1"
              href="https://itemflow-web.firebaseapp.com"
            >
              <v-icon left>web</v-icon>
              Get Started
            </v-btn>
            <v-btn
              class="my-5"
              large
              outline
              color="blue darken-1"
              href="https://github.com/zentim/itemflow-desktop/releases"
            >
              <v-icon left>computer</v-icon>
              Download
            </v-btn>
          </v-layout>
        </v-layout>

    </section>

    <section>
      <v-layout
        column
        align-center
        justify-center
        class="white--text"
      >
        <v-layout row wrap>
          <v-flex xs12 sm10 offset-sm1>
            <img
              src="@/assets/itemflow-web-homepage.png"
              height="100%"
              width="100%"
              hidden-sm-and-down>
          </v-flex>
        </v-layout>
      </v-layout>
    </section>

    <section>
      <v-layout
        column
        wrap
        class="my-5"
        align-center
      >
        <v-flex xs12 sm4 class="my-3">
          <div class="text-xs-center">
            <h2 class="headline">The best way to start learning</h2>
            <span class="subheading">
              建立你專屬的第二大腦
            </span>
          </div>
        </v-flex>
        <v-flex xs12>
          <v-container grid-list-xl>
            <v-layout row wrap align-center>
              <v-flex xs12 md4>
                <v-card>
                  <v-card-text class="text-xs-center">
                    <v-icon x-large class="blue--text text--lighten-2">widgets</v-icon>
                  </v-card-text>
                  <div class="headline text-xs-center">Component</div>
                  <div class="subheading text-xs-center">卡片組合式寫作</div>
                  <v-card-text>
                    <p>將大概念拆分成一塊塊小概念來理解，當下次遇到類似問題時，可以調出組件塊來復用，或是修改迭代，快速理清概念。</p>

                    <p>每次做主題式的學習，只需要利用關鍵字來搜尋自己過去建立的相關卡片，並按照自己的規則來組合，藉此幫助記憶與學習。</p>
                  </v-card-text>
                </v-card>
              </v-flex>
              <v-flex xs12 md4>
                <v-card>
                  <v-card-text class="text-xs-center">
                    <v-icon x-large class="blue--text text--lighten-2">gesture</v-icon>
                  </v-card-text>
                  <div class="headline text-xs-center">Context</div>
                  <div class="subheading text-xs-center">掌握知識的脈絡</div>
                  <v-card-text>
                    <p>不同背景關係甚至可決定人們對於意義之間之理解，記憶時，脈絡效應會影響記憶痕跡內容，所以從長期記憶中提取某特殊片段時，可作為一種重要的提示，使回憶更為正確。</p>

                    <p>深入大腦中原有知識之間、原有知識與當前認知對象之間的關係，大腦更擅長思考與創造，而不是記憶。</p>
                  </v-card-text>
                </v-card>
              </v-flex>
              <v-flex xs12 md4>
                <v-card>
                  <v-card-text class="text-xs-center">
                    <v-icon x-large class="blue--text text--lighten-2">translate</v-icon>
                  </v-card-text>
                  <div class="headline text-xs-center">Transfer</div>
                  <div class="subheading text-xs-center">感受學習遷移</div>
                  <v-card-text>
                    <p>先前情境所習得的知識、技能和態度，能影響另一個相似情境或新情境的學習，亦即一種學習對另一種學習的影響。</p>

                    <p>在學習過程中，遷移是不可避免的現象，因為孤立的、彼此互不影響的學習是不存在的，尋找共同要素作為認識其他類似知識的基礎。</p>
                  </v-card-text>
                </v-card>
              </v-flex>
            </v-layout>
          </v-container>
        </v-flex>
      </v-layout>
    </section>

    <section>

        <v-layout column align-center justify-center>
          <div class="headline mb-3 text-xs-center">Note-taking Application</div>
          <em>Kick-start your note today</em>
          <v-layout>
            <v-btn
              class="my-5"
              dark
              large
              color="blue darken-1"
              href="https://itemflow-web.firebaseapp.com"
            >
              <v-icon left>web</v-icon>
              Get Started
            </v-btn>
            <v-btn
              class="my-5"
              large
              outline
              color="blue darken-1"
              href="https://github.com/zentim/itemflow-desktop/releases"
            >
              <v-icon left>computer</v-icon>
              Download
            </v-btn>
          </v-layout>
        </v-layout>

    </section>

    <section>
      <v-container grid-list-xl>
        <v-layout row wrap justify-center class="my-5">
          <v-flex xs12 sm4>
            <v-card class="elevation-0 transparent">
              <v-card-title primary-title class="layout justify-center">
                <div class="headline">Company info</div>
              </v-card-title>
              <v-card-text>
                Cras facilisis mi vitae nunc lobortis pharetra. Nulla volutpat tincidunt ornare.
                Pellentesque habitant morbi tristique senectus et netus et malesuada fames ac turpis egestas.
                Nullam in aliquet odio. Aliquam eu est vitae tellus bibendum tincidunt. Suspendisse potenti.
              </v-card-text>
            </v-card>
          </v-flex>
          <v-flex xs12 sm4 offset-sm1>
            <v-card class="elevation-0 transparent">
              <v-card-title primary-title class="layout justify-center">
                <div class="headline">Contact us</div>
              </v-card-title>
              <v-card-text>
                Cras facilisis mi vitae nunc lobortis pharetra. Nulla volutpat tincidunt ornare.
              </v-card-text>
              <v-list class="transparent">
                <v-list-tile>
                  <v-list-tile-action>
                    <v-icon class="blue--text text--lighten-2">phone</v-icon>
                  </v-list-tile-action>
                  <v-list-tile-content>
                    <v-list-tile-title>XXX-XXX-XXXX</v-list-tile-title>
                  </v-list-tile-content>
                </v-list-tile>
                <v-list-tile>
                  <v-list-tile-action>
                    <v-icon class="blue--text text--lighten-2">place</v-icon>
                  </v-list-tile-action>
                  <v-list-tile-content>
                    <v-list-tile-title>XXXXX, US</v-list-tile-title>
                  </v-list-tile-content>
                </v-list-tile>
                <v-list-tile>
                  <v-list-tile-action>
                    <v-icon class="blue--text text--lighten-2">email</v-icon>
                  </v-list-tile-action>
                  <v-list-tile-content>
                    <v-list-tile-title>XXX@XXX.com</v-list-tile-title>
                  </v-list-tile-content>
                </v-list-tile>
              </v-list>
            </v-card>
          </v-flex>
        </v-layout>
      </v-container>
    </section>

  </v-container>
</template>

<script>
export default {
  name: 'HelloWorld',
  props: {
    msg: String
  }
}
</script>
