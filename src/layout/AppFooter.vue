<template>
    <footer class="footer has-cards">

        <div class="container">

            <hr>
            <div class="row align-items-center justify-content-md-between">
                <div class="col-md-6">
                    <div class="copyright">
                        &copy; {{year}}
                        Little Robots
                    </div>
                </div>
                <div class="col-md-6">
                    <ul class="nav nav-footer justify-content-end">

                        <!-- <li class="nav-item" style="padding: 0 2.5px 0 2.5px;">
                    <a target="_blank" rel="noopener" href="https://twitter.com/creativetim"
                       class="btn btn-neutral btn-icon-only btn-twitter btn-round btn-lg" data-toggle="tooltip"
                       data-original-title="Follow us">
                        <i class="fa fa-twitter"></i>
                    </a>
                        </li> -->
                        <li class="nav-item" style="padding: 0 2.5px 0 2.5px;">
                    <a target="_blank" rel="noopener" href="https://www.instagram.com/roboticalittlerobots/"
                       class="btn btn-neutral btn-icon-only btn-instagram btn-round btn-lg" data-toggle="tooltip"
                       data-original-title="Like us">
                        <i class="fa fa-instagram"></i>
                    </a>
                        </li>
                        <!-- <li class="nav-item" style="padding: 0 2.5px 0 2.5px;">
                    <a target="_blank" rel="noopener" href="https://dribbble.com/creativetim"
                       class="btn btn-neutral btn-icon-only btn-dribbble btn-lg btn-round" data-toggle="tooltip"
                       data-original-title="Follow us">
                        <i class="fa fa-dribbble"></i>
                    </a>
                        </li> -->
                        <li class="nav-item" style="padding: 0 2.5px 0 2.5px;">
                    <a target="_blank" rel="noopener" href="https://github.com/Little-Robots"
                       class="btn btn-neutral btn-icon-only btn-github btn-round btn-lg" data-toggle="tooltip"
                       data-original-title="Star on Github">
                        <i class="fa fa-github"></i>
                    </a>
                        </li>
                    </ul>
                </div>
            </div>
        </div>
    </footer>
</template>
<script>
export default {
  name: 'app-footer',
  data() {
    return {
      year: new Date().getFullYear()
    }
  }
};
</script>
<style>
</style>
