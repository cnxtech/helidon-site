<!--
  ~ Copyright (c) 2019 Oracle and/or its affiliates. All rights reserved.
-->
<template>
  <v-container v-bind:id="id" fluid light class="slide_technologies">
    <h2>Technologies</h2>
    <v-layout row wrap class="section">
      <v-flex md1 lg2/>
      <v-flex md10 lg8 pl-1 pr-1>
        <v-layout row wrap>
          <v-flex xs4 md2 lg2>
            <a href="https://netty.io" target="_blank">
              <img src="../static/img/logo-netty-500x500.png" />
              <span>Netty</span>
            </a>
          </v-flex>
          <v-flex xs4 md2 lg2>
            <a href="https://projects.eclipse.org/projects/ee4j.jersey" target="_blank">
              <img src="../static/img/logo-jersey-500x500.png" />
              <span>Jersey</span>
            </a>
          </v-flex>
          <v-flex xs4 md2 lg2>
            <a href="https://microprofile.io" target="_blank">
              <img src="../static/img/logo-microprofile-500x500.png" />
              <span>MicroProfile</span>
            </a>
          </v-flex>
          <v-flex xs4 md2 lg2>
            <a href="https://opentracing.io" target="_blank">
              <img src="../static/img/logo-opentracing-500x500.png" />
              <span>OpenTracing</span>
            </a>
          </v-flex>
          <v-flex xs4 md2 lg2>
            <a href="https://openapis.org" target="_blank">
              <img src="../static/img/logo-openapi-500x500.png" />
              <span>OpenAPI</span>
            </a>
          </v-flex>
          <v-flex xs4 md2 lg2>
            <a href="https://kubernetes.io" target="_blank">
              <img src="../static/img/logo-kubernetes-500x500.png" />
              <span>Kubernetes</span>
            </a>
          </v-flex>
          <v-flex xs4 md2 lg2>
            <a href="https://www.graalvm.org" target="_blank">
              <img src="../static/img/logo-graalvm-500x500.png" />
              <span>GraalVM</span>
            </a>
          </v-flex>
          <v-flex xs4 md2 lg2>
            <a href="https://prometheus.io" target="_blank">
              <img src="../static/img/logo-prometheus-500x500.png" />
              <span>Prometheus</span>
            </a>
          </v-flex>
          <v-flex xs4 md2 lg2>
            <a href="https://www.jaegertracing.io" target="_blank">
              <img src="../static/img/logo-jaeger-500x500.png" />
              <span>Jaeger</span>
            </a>
          </v-flex>
          <v-flex xs4 md2 lg2>
            <a href="https://zipkin.io" target="_blank">
              <img src="../static/img/logo-zipkin-500x500.png" />
              <span>Zipkin</span>
            </a>
          </v-flex>
          <v-flex xs4 md2 lg2>
            <a href="https://www.eclipse.org/eclipselink/" target="_blank">
              <img src="../static/img/logo-eclipselink-500x500.png" />
              <span>EclipseLink</span>
            </a>
          </v-flex>
          <v-flex xs4 md2 lg2>
            <a href="https://docker.io" target="_blank">
              <img src="../static/img/logo-docker-500x500.png" />
              <span>Docker</span>
            </a>
          </v-flex>
        </v-layout>
      </v-flex>
      <v-flex md1 lg2/>
    </v-layout>
  </v-container>
</template>

<script>
  export default {
    props: {
      id: {
        type: String,
        required: true
      }
    }
  }
</script>
<style lang="sass">
  .slide_technologies
    :background-color #f8f8f8
    .section
      :margin-bottom 100px
      :margin-left auto
      :margin-right auto
      :text-align center
      img
        :max-width 100%
        :max-height 200px
        :padding-top 16px
      span
        :color #595959
    a
      :text-decoration none
      :font-size large
      :margin-bottom 16px
      :text-transform uppercase
      :font-weight 300
      :text-shadow 1px 1px 1px #bdbdbd
    h2
      :color #3ea5fd
      :text-align center
      :font-weight 400
      :font-size 3em
      :margin-bottom 84px
</style>
