# load_more_button.
<div style="border: 2px solid orangered; padding: 20px;">
    <h1 style="color: orangered;">Load more - load more button with custome codding</h1><br>

    <h2 style="color: orangered;">1. HTML code formate: </h2><br>
    <p>
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

    </p>

    <h2 style="color: orangered;">1. Activarion code: </h2><br>
    <p>
      $(document).ready(function(){
        $(".col-lg-4").slice(0,3).show()
        $(".btn").on("click", function(){
            $(".col-lg-4:hidden").slice(0,3).slideDown()
            if($(".col-lg-4:hidden").length==0){
                $(".btn").fadeOut('slow')
            }
        })
      })
    </p>
  </div>

  <h2>Connect with me: <a href="https://www.linkedin.com/in/mhfaysal124/"> LinkedIn</a></h2>
