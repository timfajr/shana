vue <template lang="">
  <div
    class="h-screen mx:auto bg-grey-500 object-contain md:object-scale-down md-6 md:min-h-full "
  >
    <div class="grid grid-flow-col grid-rows-4 grid-cols-4 w-full h-full bg-grey-500">
      <div class="row-start-4 col-start-1 row-span-1 col-span-4 bg-blue-700 ">
        <div class=" grid grid-flow-col grid-cols-3 grid-rows-1 text-center h-8 w-full">
          <div class="col-start-1 bg-white pt-3 h-12">
            1
          </div>
          <div class="col-start-2 bg-white pt-3 h-12">
            2
          </div>
          <div class="col-start-3 bg-white pt-3 h-12">
            3
          </div>
        </div>
      </div>
      <div class="p-3 row-start-1 row-span-3 col-start-4 bg-yellow-400">
        2
      </div>
      <div class="relative p-3 row-start-1 col-start-1 col-span-3 row-span-3 bg-blue-800 shadow-inner">
        <div class="absolute box-content left-0" >
        <Logo class="mx-auto pt-5 bg-white" />
        </div>
      </div>
    </div>
  </div>
  </div>
</template>
<script>
export default {

}
</script>
<style lang="">

</style>
