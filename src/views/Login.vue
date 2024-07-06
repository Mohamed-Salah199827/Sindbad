<template>
  <section class="login">
    <div class="form">
      <h3>تسجيل الدخول لشركتك</h3>
      <form class="mt-4">
        <div class="form-group mb-3">
          <label for="exampleInputEmail1" class="mb-1">البريد الإلكتروني</label>
          <input
            type="email"
            class="form-control p-3 bg-light"
            id="exampleInputEmail1"
            aria-describedby="emailHelp"
          />
        </div>
        <div class="form-group">
          <label for="exampleInputPassword1" class="mb-1">كلمة المرور</label>
          <input
            type="password"
            class="form-control p-3 bg-light"
            id="exampleInputPassword1"
          />
        </div>

        <button type="submit" class="btn btn-primary w-100 mt-3 py-2">
          تسجيل دخول
        </button>
        <div class="d-flex justify-content-between mt-2">
          <p class="fw-bold" style="color: #fba538">نسيت كلمة المرور؟</p>
          <p class="fw-bold" style="color: #fba538">
            إعادة التحقق من البريد الإلكتروني
          </p>
        </div>
        <div class="d-flex justify-content-center newAccount">
          <p>ليس لديك حساب؟</p>
          <a href="" style="">حساب جديد</a>
        </div>
      </form>
    </div>
    <div class="image">
      <img src="@/../public/images/Frame.png" alt="" />
    </div>
  </section>
</template>

<script>
export default {};
</script>

<style lang="scss" scoped>
.login {
  margin: auto;
  width: 80%;
  display: flex;
  h3 {
    color: #333333;
  }
  .form {
    width: 50%;
  }
  .image {
    width: 40%;
    margin-right: 1vw;
    img {
      width: 100%;
    }
  }
  label {
    color: #666666;
  }
  button {
    background-color: var(--main-color);

    font-family: Cairo;
    font-size: 24px;
    font-weight: 600;
    line-height: 44.98px;
    text-align: center;
  }
  .newAccount {
    p {
      font-family: Cairo;
      font-size: 21px;
      font-weight: 500;
      line-height: 39.35px;
      text-align: right;
      color: #000000;
    }
    a {
      font-family: Cairo;
      font-size: 21px;
      font-weight: 700;
      line-height: 39.35px;
      text-align: right;
      color: var(--main-color);
      margin-right: 7px;
      text-decoration: none;


    }
  }
}
</style>
