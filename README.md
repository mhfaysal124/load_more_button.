
<div style="border: 2px solid orangered; padding: 20px;">
    <h1 style="color: orangered;">Load more - load more button with custom coding</h1><br>
    <h2>Click here for live view: <a href="https://mhfaysal124.github.io/load_more_button./" target="blank">Demo</a></h2>
<h2 style="color: orangered;">1. HTML code formate: </h2><br>
    

          <div class="col-lg-4 pb-4">
            <img src="img/img_2.jpg" class="img-fluid " alt="Load more button mhfasyal">
            <h3 class="text-white text-center bg-danger p-3 fw-bold">MH Faysal</h3>
          </div>

          <div class="col-lg-4 pb-4">
            <img src="img/img_2.jpg" class="img-fluid " alt="Load more button mhfasyal">
            <h3 class="text-white text-center bg-danger p-3 fw-bold">MH Faysal</h3>
          </div> 

          <div class="col-lg-4 pb-4">
            <img src="img/img.jpg" class="img-fluid " alt="Load more button mhfasyal">
            <h3 class="text-white text-center bg-danger p-3 fw-bold">MH Faysal</h3>
          </div>      

          <div class="col-lg-4 pb-4">
            <img src="img/img_1.jpg" class="img-fluid " alt="Load more button mhfasyal">
            <h3 class="text-white text-center bg-danger p-3 fw-bold">MH Faysal</h3>
          </div>

          <div class="col-lg-12 text-center">
            <div class="btn btn-warning fw-bold mb-5">LOAD MORE</div>
          </div>



<h2 style="color: orangered;">1. Activation code: </h2><br>


      $(document).ready(function(){
        $(".col-lg-4").slice(0,3).show()
        $(".btn").on("click", function(){
            $(".col-lg-4:hidden").slice(0,3).slideDown()
            if($(".col-lg-4:hidden").length==0){
                $(".btn").fadeOut('slow')
            }
        })
      })

  </div>

   <h1>Connect with MH Faysal</h1>
    <h2>LinkedIn profile: <a href="https://www.linkedin.com/in/mhfaysal124/">LinkedIn</a></h2>
    <h2>Facebook page: <a href="https://www.facebook.com/mhfaysal124">Facebook</a></h2>
    <h2>My website: <a href="https://www.mhfaysal.com">MH Faysal</a></h2>
