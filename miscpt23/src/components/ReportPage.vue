<template>
  <div class="home">
    <div class="common-layout">

      <el-container>
      <el-container>
        <el-header>
          <h1 id="MISCSIM23">Misc Path Tracing Implementations</h1>
        </el-header>
        <el-container>
          <el-container>
            <el-main>
              <el-row class="row-bg"><br/></el-row>
              <el-row class="row-bg" justify="left">
                <p style="text-align:left">
                  This page includes some of miscellaneous path tracing implementation results written in 2022 ~ 2023. 
                  They are course assignments of <el-link href="https://cseweb.ucsd.edu/~tzli/cse272/wi2023/" target="_blank" type="primary">CSE 272</el-link>
                  instructed by Professor <el-link href="https://cseweb.ucsd.edu/~tzli/" target="_blank" type="primary">Tzu-Mao Li</el-link>.
                  This page only includes path tracing algorithms implementation based on <el-link href="https://github.com/BachiLi/lajolla_public" target="_blank" type="primary">lajolla Renderer</el-link>,
                  more implementation based on <el-link href="https://github.com/SuikaSibyl/SIByLEngine2023/" target="_blank" type="primary">my own Engine</el-link>  are listed on its 
                  <el-link href="https://github.com/SuikaSibyl/SIByLEngine2023/wiki/SIByL-Renderer/" target="_blank" type="primary">Github Wiki</el-link>.
                </p>
              </el-row>

              <!-- Chapter 1: Introduction -->
              <el-row class="row-bg">
                <h2 id="1. Introduction" style="text-align:left">1. Disney Principled BSDF</h2>
              </el-row>
              
              <el-row class="row-bg" justify="center">
                <el-col :span="16">
                  <el-image style="align:center" src="https://imagehost-suikasibyl-us.oss-us-west-1.aliyuncs.com/img/disney_principle_array.png" />
                  <p><code>
                    Material Balls Array
                  </code></p>
                </el-col>
              </el-row>

              <el-row class="row-bg" justify="center">
                <el-col :span="16">
                  <el-image style="align:center" src="https://imagehost-suikasibyl-us.oss-us-west-1.aliyuncs.com/img/disney_principled.png" />
                  <p><code>
                    PBR Tank
                  </code></p>
                </el-col>
              </el-row>

              <!-- Chapter 1: Introduction -->
              <el-row class="row-bg">
                <h2 id="1. Introduction" style="text-align:left">2. Volumetric Path Tracing</h2>
              </el-row>
              
              <el-row class="row-bg" justify="center">
                <el-col :span="16">
                  <el-image style="align:center" src="https://imagehost-suikasibyl-us.oss-us-west-1.aliyuncs.com/img/vol6.png" />
                  <p><code>
                    Three Spheres
                  </code></p>
                </el-col>
              </el-row>

              <el-row class="row-bg" justify="center">
                <el-col :span="16">
                  <el-image style="align:center" src="https://imagehost-suikasibyl-us.oss-us-west-1.aliyuncs.com/img/vol_cbox.png" />
                  <p><code>
                    Volumetric Cornell Box
                  </code></p>
                </el-col>
              </el-row>

              <el-row class="row-bg" justify="center">
                <el-col :span="16">
                  <el-image style="align:center" src="https://imagehost-suikasibyl-us.oss-us-west-1.aliyuncs.com/img/hetvol_colored.png" />
                  <p><code>
                    Heterogeneous Colored
                  </code></p>
                </el-col>
              </el-row>

              <el-row class="row-bg" justify="center">
                <el-col :span="16">
                  <el-image style="align:center" src="https://imagehost-suikasibyl-us.oss-us-west-1.aliyuncs.com/img/volumetric.png" />
                  <p><code>
                    Chimney
                  </code></p>
                </el-col>
              </el-row>

            </el-main>
            <el-divider />
            <el-footer>
              <el-link href="https://suikasibyl.github.io/" target="_blank" type="primary">My Homepage</el-link>
            </el-footer>
          </el-container>
        </el-container>
      </el-container>
    </el-container>
    </div>
  </div>
</template>

<style scoped>
.el-link {
  margin-right: 8px;
}
.el-link .el-icon--right.el-icon {
  vertical-align: text-bottom;
}
</style>

<script>

import '../assets/githubmd.css';

export default {
  name: 'ReportPage',
  mounted() {
  },
  props: {
  },
  data() {
    return {
      formula: '$$x = {-b \\pm \\sqrt{b^2-4ac} \\over 2a}.$$'
    }
  },
}
</script>
