
<template>
  
    <div>
      <!-- 네비게이션 바 시작 -->
      <Navbar /> 
      <!-- 네비게이션 바 끝 -->
  
      <!-- 페이지 헤더 시작 -->
      <div class="container-fluid page-header py-4 mb-2 wow fadeIn" data-wow-delay="0.1s">
        <div class="container text-center py-5">
          <h1 class="display-5 text-white mb-4 animated slideInDown">아이디 찾기</h1>
          <nav aria-label="breadcrumb animated slideInDown">
            <!-- Breadcrumb (경로) -->
          </nav>
        </div>
      </div>
      <!-- 페이지 헤더 끝 -->
  
      <div class="container-fluid py-5">
        <div class="container">
          <div class="row justify-content-center">
            <div class="col-lg-7">
              <div class="rounded p-4 p-sm-5 wow fadeInUp maincol" data-wow-delay="0.1s">
                <div class="row g-3">
                  <label for="Name" class="form-label">이름</label>
                  <input type="text" class="form-control" id="name" placeholder="아이디를 입력하세요">
                  <label for="Email" class="form-label">이메일</label>
                  <input type="text" class="form-control" id="email" placeholder="이메일을 입력하세요">
                  <button type="button" class="btn btn-primary mt-3 btnall">아이디 찾기</button>
                </div>
              </div>
            </div>
          </div>
        </div>
      </div>
  
      <!-- 저작권 시작 -->
      <Footer />
      <!-- 저작권 끝 -->

    </div>
    
  </template>
  <script>
import Navbar from '@/components/Navbar/Navbar.vue';
import Footer from '@/components/Footer/Footer.vue';
export default {
  components: {
    Navbar,
    Footer,
  }
};
  </script>