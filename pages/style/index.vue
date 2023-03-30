<template>
    <div class="wrap">
        <div class="contents">
            <h2>그리드</h2>
            <div class="container">
                <div class="box-container rounded col-12">
                  <div class="box-container__title">
                      <h4>타이포그래피</h4>
                      <span>조형성과 가변성이 뛰어난 Pretendard 폰트를 선택하였으며 UX 중요도에 따라 강약이 조절되며 적재적소에 사용됩니다.
                      </span>
                  </div>
                  <h1>h1. 페이지 타이틀에 사용됩니다</h1>
                  <h2>h2. 대쉬보드 타이틀에 사용됩니다</h2>
                  <h3>h3. 페이지 서브 타이틀에 사용됩니다</h3>
                  <h4>h4. 대쉬보드 서브 타이틀에 사용됩니다</h4>
                  <h5>SemiBold 안녕하세요 16px</h5>
                  <p class="body-light">Light 안녕하세요 16px</p>
                  <p class="body-regular">Regular 안녕하세요 16px</p>
                  <p class="body-medium">Medium 안녕하세요 16px</p>
                  <p class="body-semibold">SemiBold 안녕하세요 16px</p>
                  <span>Regular 안녕하세요 14px</span>
                  <span class="caption">Regular 안녕하세요 12px</span>
                  <span class="small">Regular 안녕하세요 10px</span>
                </div>

                <div class="box-container rounded col-6">d</div>
                <div class="box-container rounded col-6">d</div>
                <div class="box-container rounded col-3">d</div>
                <div class="box-container rounded col-3">d</div>
                <div class="box-container rounded col-3">d</div>
            </div>

        </div>
    </div>
  </template>
  
  <script>
  export default {
    layout: 'style',
  }
  </script>
  
  <style lang="scss" scoped>
    .wrap {
        width: 100%;
        height: 100%;
        .contents {
            min-height: calc(100vh - 57px);
            padding: 48px 40px 100px;
            background-color: $slate-50;
        }
    }
</style>