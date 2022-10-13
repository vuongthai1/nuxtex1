<template>
  <div>
    <div class="header">
      <div class="header__title">Summer sale for all swim suits - off 50%!</div>
      <div class="header__container">
        <div class="header__sizebar">
          <div class="header__logo"><img src="image/Capture.PNG" alt="" /></div>
          <div class="header__item">Shop</div>
          <div class="header__item">Category</div>
          <div class="header__item">Men</div>
          <div class="header__item">Women</div>
          <div class="header__item">Pages</div>
          <div class="disable__item">Blog</div>
          <div class="disable__item">Contact</div>
        </div>
        <div class="header__icon">
          <div class="icon__item"><i class="ri-search-line"></i></div>
          <div class="icon__item"><i class="ri-user-line"></i></div>
        </div>
      </div>
    </div>
    <div>
      <div class="line"></div>
    </div>
    <div class="container">
      <div class="container__home">
        <div class="home__item">Home</div>
        <div class="home__item"><i class="ri-arrow-right-s-line"></i></div>
        <div class="home__item">Blog</div>
      </div>
      <div class="container__title">Latest news from yobazar</div>
      <div class="container__sizebar">
        <div class="container__item">Jeans</div>
        <div class="container__item">Jackets & Coats</div>
        <div class="focused__item">Underwear</div>
        <div class="container__item">Shirts</div>
        <div class="container__item">Suits</div>
        <div class="container__item">Swimwear</div>
      </div>
      <div class="container__card">
        <div class="card__item">
          <div class="card__span"></div>
          <div class="card__img"><img src="image/7.png" alt="" /></div>
          <div class="card__content">
            The best ways to change your summer wardrobe into autumn wardrobe.
          </div>
          <div class="day__upload">March 05, 2020</div>
        </div>
        <div class="card__item">
          <div class="card__span"></div>
          <div class="card__img"><img src="image/8.png" alt="" /></div>
          <div class="card__content">
            The best ways to change your summer wardrobe into autumn wardrobe.
          </div>
          <div class="day__upload">March 05, 2020</div>
        </div>
        <div class="card__item">
          <div class="card__span"></div>
          <div class="card__img"><img src="image/9.png" alt="" /></div>
          <div class="card__content">
            The best ways to change your summer wardrobe into autumn wardrobe.
          </div>
          <div class="day__upload">March 05, 2020</div>
        </div>
        <div class="card__item">
          <div class="card__span"></div>
          <div class="card__img"><img src="image/1.png" alt="" /></div>
          <div class="card__content">
            The best ways to change your summer wardrobe into autumn wardrobe.
          </div>
          <div class="day__upload">March 05, 2020</div>
        </div>
        <div class="card__item">
          <div class="card__img"><img src="image/2.png" alt="" /></div>
          <div class="card__content">
            The best ways to change your summer wardrobe into autumn wardrobe.
          </div>
          <div class="day__upload">March 05, 2020</div>
        </div>
        <div class="card__item">
          <div class="card__span"></div>
          <div class="card__img"><img src="image/3.png" alt="" /></div>
          <div class="card__content">
            The best ways to change your summer wardrobe into autumn wardrobe.
          </div>
          <div class="day__upload">March 05, 2020</div>
        </div>
        <div class="card__item">
          <div class="card__thumbnail">
            <div>
              <div class="card__chip">test</div>
              <div class="card__chip">test</div>
            </div>
            <div class="card__img"><img src="image/4.png" alt="" /></div>
          </div>

          <div class="card__content">
            The best ways to change your summer wardrobe into autumn wardrobe.
          </div>
          <div class="day__upload">March 05, 2020</div>
        </div>
        <div class="card__item">
          <div class="card__thumbnail">
            <div class="card__chip">test</div>
            <div class="card__img"><img src="image/5.png" alt="" /></div>
          </div>
          <div class="card__content">
            The best ways to change your summer wardrobe into autumn wardrobe.
          </div>
          <div class="day__upload">March 05, 2020</div>
        </div>
        <div class="card__item">
          <div class="card__img"><img src="image/6.png" alt="" /></div>
          <div class="card__content">
            The best ways to change your summer wardrobe into autumn wardrobe.
          </div>
          <div class="day__upload">March 05, 2020</div>
        </div>
        <div class="pagination">
          <div class="pagination__item">
            <div class="pagination__number">a</div>
          </div>
          <div class="pagination__item">
            <div class="pagination__number">1</div>
          </div>
          <div class="pagination__item">
            <div class="pagination__number">2</div>
          </div>
          <div class="pagination__item">
            <div class="pagination__number">3</div>
          </div>
          <div class="pagination__item">
            <div class="pagination__number">4</div>
          </div>
          <div class="pagination__item">
            <div class="pagination__number">5</div>
          </div>
          <div class="pagination__item">
            <div class="pagination__number">6</div>
          </div>
          <div class="pagination__item">
            <div class="pagination__number">7</div>
          </div>
          <div class="pagination__item">
            <div class="pagination__number">b</div>
          </div>
        </div>
      </div>
      <div class="info__bar">
        <div class="info__bar__item">11</div>
        <div class="info__bar__item">11</div>
        <div class="info__bar__item">11</div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  props: {
    post: { type: Object, default: null },
  },
};
</script>
<style lang="scss" scoped>
.header {
  width: 100%;
  height: 120px;
  top: 0;
  .header__title {
    position: absolute;
    width: 100%;
    height: 30px;
    left: 0px;
    top: 0px;
    background: #ffeeef;
    font-family: "Jost";
    font-style: normal;
    font-weight: 400;
    font-size: 13px;
    line-height: 20px;
    text-align: center;
    flex: none;
    order: 0;
    flex-grow: 0;
    color: #191919;
    padding-top: 3px;
  }
  .header__container {
    padding-top: 30px;
    width: 100%;
    display: flex;
    .header__logo {
      position: absolute;
      width: 39px;
      height: 25px;
      left: 184px;
      top: 75px;
      bottom: 10px;
      padding-left: 21px;
    }
    .header__icon {
      position: absolute;
      width: 150px;
      height: 35px;
      left: 85%;
      right: 10%;
      top: 95px;
      bottom: 100%;
      display: flex;
      .icon__item {
        display: flex;
        justify-content: center;
        margin: auto;
      }
    }
    .header__sizebar {
      padding-left: 543px;
      padding-right: 544px;
      padding-top: 62px;
      padding-bottom: 32px;
      display: flex;
      flex-wrap: nowrap;
      .header__item {
        justify-content: center;
        margin: 0 30px 0 30px;
        height: 25px;
        font-family: "Jost";
        font-style: normal;
        font-weight: 500;
        font-size: 17px;
        line-height: 25px;
        /* identical to box height */
        color: #191919;
        /* Inside auto layout */
        flex: none;
        order: 0;
        flex-grow: 0;
      }
      .disable__item {
        justify-content: center;
        margin: 0 30px;
        width: 39px;
        height: 25px;
        font-family: "Jost";
        font-style: normal;
        font-weight: 400;
        font-size: 17px;
        line-height: 25px;
        /* identical to box height */
        color: #191919;
        /* Inside auto layout */
        flex: none;
        order: 0;
        flex-grow: 0;
      }
    }
  }
}
.line {
  position: absolute;
  width: 100%;
  height: 1px;
  left: 0px;
  background: #e6e6e6;
  margin: 20px;
}
.container {
  padding-left: 185px;
  .container__home {
    width: 34px;
    height: 19px;
    padding: 7px;
    font-family: "Jost";
    font-style: normal;
    font-weight: 400;
    font-size: 13px;
    line-height: 19px;
    /* identical to box height */
    color: #808080;
    display: flex;
    justify-content: space-between;
    flex-wrap: nowrap;
    margin: 20px;
    .home__item {
      margin: 3px;
    }
  }
  .container__title {
    padding: 21px;
    width: 444px;
    height: 52px;
    color: #191919;
    font-family: "Jost";
    font-style: normal;
    font-weight: 500;
    font-size: 40px;
    line-height: 52px;
    /* identical to box height, or 52px */

    color: #191919;

    /* Inside auto layout */

    flex: none;
    order: 0;
    flex-grow: 0;
  }
  .container__sizebar {
    padding: 20px;
    display: flex;
    margin: auto;
    font-family: "Jost";
    font-style: normal;
    font-weight: 400;
    font-size: 17px;
    line-height: 25px;
    /* identical to box height */
    color: #191919;
    /* Inside auto layout */
    flex: none;
    order: 0;
    flex-grow: 0;
    text-align: center;

    .container__item {
      font-family: "Jost";
      font-style: normal;
      font-weight: 500;
      font-size: 17px;
      line-height: 25px;
      margin: 0 30px;
      margin-left: 0px;
      /* identical to box height */
      color: #191919;
      /* Inside auto layout */
      flex: none;
      order: 0;
      flex-grow: 0;
    }
    .focused__item {
      margin-left: -10px;
      margin: -1px 30px;
      font-weight: 500;
      text-decoration: underline;
      /* identical to box height */
      color: #191919;
      /* Inside auto layout */
      flex: none;
      order: 0;
      flex-grow: 0;
    }
  }
  .container__card {
    display: flex;
    flex-wrap: wrap;
    .card__item {
      transition: 0.3s;
      width: 33%;
      border-radius: 5px;
      height: 400px;
      box-sizing: border-box;
      .card:hover {
        box-shadow: 0 8px 16px 0 rgba(0, 0, 0, 0.2);
      }
      .card__image {
        display: flex;
        padding: 20px;
      }
      .card__content {
        width: 370px;
        height: 96px;

        font-family: "Jost";
        font-style: normal;
        font-weight: 400;
        font-size: 25px;
        line-height: 130%;
        /* or 32px */

        text-align: center;

        color: #191919;

        /* Inside auto layout */

        flex: none;
        order: 0;
        flex-grow: 0;
      }
      .day__upload {
        width: 370px;
        height: 19px;
        font-family: "Jost";
        font-style: normal;
        font-weight: 400;
        font-size: 13px;
        line-height: 19px;
        /* identical to box height */
        text-align: center;
        color: #191919;
        /* Inside auto layout */
      }
      .card__thumbnail {
        position: relative;
      }
      .card__chip {
        padding: 0px 10px;
        gap: 13px;
        text-align: center;
        background: #ffffff;
        border-radius: 55px;
        position: absolute;
        top: 4px;
        left: 4px;
        z-index: 99;
        display: flex;
      }
    }
    .pagination {
      display: flex;
      flex-direction: row;
      align-items: center;
      gap: 6px;
      position: absolute;
      width: 306px;
      height: 34px;
      left: 42%;
      top: 1530px;
      .pagination__item {
        display: flex;
        flex-wrap: wrap;
        box-sizing: border-box;
        width: 34px;
        height: 34px;
        border: 1px solid #cf4949;
        border-radius: 42px;
        /* Inside auto layout */
        flex: none;
        order: 1;
        flex-grow: 0;
        text-align: center;
      }
      .pagination__number {
        padding-left: 12px;
        text-align: center;
        position: absolute;
        width: 9px;
        height: 20px;
        top: 6.5px;
        font-family: "Jost";
        font-style: normal;
        font-weight: 600;
        font-size: 14px;
        line-height: 20px;
        color: #191919;
      }
    }
  }
  .info__bar {
    position: absolute;
    width: 1230px;
    height: 73px;
    left: 185px;
    top: 1630px;
  }
  .info__bar__item {
    /* Auto layout */
    display: flex;
    flex-direction: row;
    align-items: center;
  }
}
</style>
