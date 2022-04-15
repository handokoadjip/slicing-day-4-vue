<template>
  <section>
    <div class="container mb-5 py-5">
      <div class="row">
        <div class="col-lg-3 d-flex align-items-center mt-5 pt-5">
          <div class="wrapper text-center text-lg-start">
            <nav class="text-uppercase">
              <router-link class="text-decoration-none mb-2 d-block" to="#"><i
                  class="far fa-user text-primary me-3"></i>milan
                vuckovic</router-link>
              <router-link class="text-decoration-none mb-2 d-block" to="#"><i
                  class="far fa-calendar-alt text-primary me-3"></i>25 july 2015</router-link>
              <router-link class="text-decoration-none mb-2 d-block" to="#"><i
                  class="far fa-bookmark text-primary me-3"></i>
                travel</router-link>
            </nav>
          </div>
        </div>
        <div class="col-lg-6">
          <div class="wrapper fs-5">
            <p>
              Lorem ipsum, dolor sit amet consectetur adipisicing elit. Quidem est, dignissimos quia tenetur error
              dolore commodi perspiciatis quo voluptates? Voluptate harum, unde cupiditate tempora totam cumque
              asperiores libero vitae, molestias fugiat iure ipsum explicabo eum modi obcaecati itaque maiores
              debitis, consectetur pariatur non dolorem quo. Adipisci expedita numquam quibusdam dolore.
            </p>
            <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Molestiae ipsam, beatae ipsum fugiat nemo enim
              quasi est! Neque, corrupti veritatis?</p>
            <p>Lorem ipsum dolor sit, amet consectetur adipisicing elit. Iure, molestiae voluptate. Ab voluptatibus
              pariatur sequi architecto aliquam cum aspernatur culpa dolorum impedit blanditiis quos molestias
              exercitationem ducimus placeat, expedita voluptatum et veniam repellat voluptate labore!</p>
          </div>
        </div>
      </div>
    </div>
    <div class="container mb-5 py-5">
      <div class="row">
        <div class="col-lg-9 justify-content-center">
          <figure>
            <img class="h-image-600px w-100" src="@/assets/source/image/img-1.jpg" alt="image-1">
          </figure>
        </div>
        <div class="col-lg-3 d-flex align-items-center mt-5 pt-5 mt-4">
          <div class="wrapper">
            <div class="list-text"></div>
            <p class="text-uppercase ls-3px fs-7">iceland by anders jilden / unsplash</p>
          </div>
        </div>
      </div>
    </div>
    <div class="container mb-5 py-5">
      <div class="row">
        <div class="col-lg-3 d-flex align-items-center mt-5 pt-5">
          <div class="wrapper text-center text-lg-start">
            <p class="fs-4 border-top-primary-2px pt-4 ff-merriweather mb-4">Lorem ipsum dolor sit amet consectetur
              adipisicing elit. Iusto rerum voluptates nulla, eligendi obcaecati delectus!</p>
            <p class="text-uppercase d-flex align-items-center fs-6"><i
                class="far fa-2x fa-user-circle text-primary me-3"></i>richard bach</p>
          </div>
        </div>
        <div class="col-lg-6">
          <div class="wrapper fs-5">
            <div class="text">
              <p>
                Lorem ipsum, dolor sit amet consectetur adipisicing elit. Quidem est, dignissimos quia tenetur error
                dolore commodi perspiciatis quo voluptates? Voluptate harum, unde cupiditate tempora totam cumque
                asperiores libero vitae, molestias fugiat iure ipsum explicabo eum modi obcaecati itaque maiores
                debitis, consectetur pariatur non dolorem quo. Adipisci expedita numquam quibusdam dolore.
              </p>
              <p>Lorem ipsum dolor sit, amet consectetur adipisicing elit. Iure, molestiae voluptate. Ab voluptatibus
                pariatur sequi architecto aliquam cum aspernatur culpa dolorum impedit blanditiis quos molestias
                exercitationem ducimus placeat, expedita voluptatum et veniam repellat voluptate labore!</p>
              <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Molestiae ipsam, beatae ipsum fugiat nemo
                enim quasi est! Neque, corrupti veritatis?</p>
              <p>
                Lorem ipsum, dolor sit amet consectetur adipisicing elit. Quidem est, dignissimos quia tenetur error
                dolore commodi perspiciatis quo voluptates? Voluptate harum, unde cupiditate tempora totam cumque
                asperiores libero vitae, molestias fugiat iure ipsum explicabo eum modi obcaecati itaque maiores
                debitis, consectetur pariatur non dolorem quo. Adipisci expedita numquam quibusdam dolore.
              </p>
            </div>
            <div class="comment">
              <div class="love-share d-flex justify-content-center my-4 py-4">
                <p class="text-uppercase d-flex align-items-center fs-6 me-5"><i
                    class="fas fa-heart text-primary me-3"></i>827 likes</p>
                <p class="text-uppercase d-flex align-items-center fs-6"><i class="fas fa-share-alt me-3"></i>share
                  this</p>
              </div>
              <div class="form">
                <form action="" method="post">
                  <div class="mb-3">
                    <textarea class="form-control" name="comment" id="comment" cols="30" rows="8"
                      placeholder="Type your comment here"></textarea>
                  </div>
                  <div class="mb-3 float-end">
                    <button class="btn btn-light text-uppercase py-3 px-5">send comment</button>
                  </div>
                </form>
              </div>
            </div>
          </div>
        </div>
        <div class="col-lg-3 d-flex mt-5 pt-5">
          <div class="wrapper text-center text-lg-start w-100">
            <figure>
              <img class="w-100 h-image-200px border-top-primary-2px py-3" src="@/assets/source/image/img-2.jpg"
                alt="image-2">
            </figure>
            <p class="text-uppercase text-primary fs-7 mb-2">also recomended</p>
            <p class="ff-merriweather text-capitalize fs-4">how to teach english and live in spain</p>

          </div>
        </div>
      </div>
    </div>
  </section>
</template>

<script>
export default {
  name: "ContentComponent",
}
</script>