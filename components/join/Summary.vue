<template>
  <section>
    <div id="contact" class="max-w-6xl mx-auto px-4 sm:px-6">
      <div class="pb-12 md:pb-20">
        <div
          class="bg-primary rounded py-10 px-8 md:py-12 md:px-12 shadow-2xl"
          data-aos="zoom-y-out"
        >
          <div class="flex flex-col justify-between items-center">
            <h3 class="hidden md:flex mb-6 h3 text-white text-center mb-2">
              加入和瑛社，<br />
              熔铸兴趣与热爱，施展才华和本领。汲取知识、开启思路。<br />
              尽享优势资源，站位高端平台。同我们一起成功！
            </h3>
            <h3 class="md:hidden mb-6 h3 text-white text-center mb-2">
              加入和瑛社，<br />
              熔铸兴趣与热爱，<br />
              施展才华和本领。<br />
              汲取知识、开启思路。<br />
              尽享优势资源，站位高端平台。<br />
              同我们一起成功！
            </h3>
            <NuxtLink
              class="btn btn-lg btn-wide text-primary bg-gradient-to-r from-red-100 to-white"
              @click="showToast('联系邮箱：hr@heryin.net')"
              to="mailto:hr@heryin.net"
            >
              加入和瑛
            </NuxtLink>
          </div>
        </div>
      </div>
    </div>
  </section>
</template>

<script setup lang="ts">
const showToast = inject<Function>('showToast', () => {})
</script>
