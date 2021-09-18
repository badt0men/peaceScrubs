 <template>
  <div class="footer_wrap">
    <!-- Footer Start -->
    <div class="flex-grow-1"></div>
    <div class="app-footer">
      <div class="row">
        <div class="col-md-9">
          <p><strong>{{currentUser.footer}}</strong></p>
        </div>
      </div>
      <div
        class="footer-bottom border-top pt-3 d-flex flex-column flex-sm-row align-items-center"
      >
        <div class="d-flex align-items-center">
          <img class="logo" :src="'/images/'+currentUser.logo" alt width="60" height="60">
          <div>
            <div>
              <!-- <p class="m-0">Copyright &copy; 2021 {{$t('developed_by')}} {{currentUser.developed_by}}</p> -->
              <p class="m-0"><b>Welcome to Peace Scrubs</b> <br/>
              We offer a wide variety of medical uniforms and nurse scrubs for both males and females. Our medical uniforms and nurse scrubs are of premium quality and affordable with the best price for your money. Whether you are looking for pants, jackets, tops, lab coats, you surely will find the best quality and brand at Peace Scrubs Store.</p>
              <p class="m-0">Copyright &copy; 2021. All rights reserved. </p>
              </div>
          </div>
          <span class="flex-grow-1"></span>
        </div>
      </div>
      <!-- fotter end -->
    </div>
  </div>
</template> 
<script>
import { mapGetters, mapActions } from "vuex";

export default {
  data() {
    return {};
  },
  computed: {
     ...mapGetters([
       "currentUser",
    ]),
  },

  methods: {}
};
</script>


<style lang="scss" scoped>
</style> 