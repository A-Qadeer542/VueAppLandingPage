<template>
  <div class="community-section">
    <div class="heading" data-aos="fade-up" data-aos-duration="2000">
      Join the <span>bizly</span> community
    </div>
    <div class="para" data-aos="fade-up" data-aos-duration="2000">
      This is a very exciting time for the <span>bizly</span> community. We are
      thrilled to bring a unique platform to the market designed to
      revolutionize the way professionals network. Join us on our journey and be
      a part of shaping the future of networking while being one of the first to
      experience what <span>bizly</span>
      has to offer.
    </div>
    <div class="card-wrapper" data-aos="fade-up" data-aos-duration="2000">
      <div class="card-body">
        <div class="card-heading">Exclusive Updates</div>
        <div class="card-para">
          Get updates on the development from the <span>bizly</span> team on our
          private discord channel!
        </div>
      </div>
      <div class="card-body">
        <div class="card-heading">Make a Difference</div>
        <div class="card-para">
          Get exclusive access to vote on certain design decisions, features,
          and <span>bizly</span>-related events.
        </div>
      </div>
      <div class="card-body">
        <div class="card-heading">Test the App</div>
        <div class="card-para">
          Test the app and give your feedback in one-on-one or group video calls
          with the <span>bizly</span> team!
        </div>
      </div>
      <div class="card-body">
        <div class="card-heading">Special Offers</div>
        <div class="card-para">
          As an early adopter, receive exclusive benefits like discounted rates,
          VIP event passes, and more!
        </div>
      </div>
    </div>
    <div class="party-heading">Join the party!</div>
    <div class="form-wrapper">
      <form class="row g-5">
        <div class="col-md-6 firstName">
          <label for="firstName" class="form-label">First Name </label>
          <input type="text" class="form-control" aria-label="First name" />
        </div>
        <div class="col-md-6 lastName">
          <label for="lastName" class="form-label">Last Name </label>
          <input type="text" class="form-control" aria-label="First name" />
        </div>
        <div class="col-12 email">
          <label for="inputEmail4" class="form-label">Email</label>
          <input type="email" class="form-control" id="inputEmail4" />
        </div>
        <div class="col-md-12">
          <p class="appCheckLabel">Which industry best defines you?</p>
          <div class="form-check">
            <input
              class="form-check-input"
              type="radio"
              name="flexRadioDefault"
              id="flexRadioDefault1"
            />
            <label class="industryChecked" for="flexRadioDefault1"></label>

            <label class="form-check-label" for="flexRadioDefault1">
              Creative
            </label>
          </div>
          <div class="form-check">
            <input
              class="form-check-input"
              type="radio"
              name="flexRadioDefault"
              id="flexRadioDefault2"
            />
            <label class="industryChecked" for="flexRadioDefault2"></label>

            <label class="form-check-label" for="flexRadioDefault2">
              Talent / Performer
            </label>
          </div>
          <div class="form-check">
            <input
              class="form-check-input"
              type="radio"
              name="flexRadioDefault"
              id="flexRadioDefault3"
            />
            <label class="industryChecked" for="flexRadioDefault3"></label>

            <label class="form-check-label" for="flexRadioDefault3">
              Business Professional
            </label>
          </div>
        </div>
        <div class="col-12">
          <p class="appCheckLabel">What is your main use for the app?</p>
          <div class="form-check">
            <input class="form-check-input" type="checkbox" id="gridCheck" />
            <label class="checked" for="gridCheck"></label>
            <label class="form-check-label" for="gridCheck"> Networking </label>
          </div>
          <div class="form-check">
            <input class="form-check-input" type="checkbox" id="gridCheck1" />
            <label class="checked" for="gridCheck1"></label>
            <label class="form-check-label" for="gridCheck1">
              Collaborating
            </label>
          </div>
          <div class="form-check">
            <input class="form-check-input" type="checkbox" id="gridCheck3" />
            <label class="checked" for="gridCheck3"></label>
            <label class="form-check-label" for="gridCheck3">
              Looking For Opportunities
            </label>
          </div>
          <div class="form-check">
            <input class="form-check-input" type="checkbox" id="gridCheck4" />
            <label class="checked" for="gridCheck4"></label>
            <label class="form-check-label" for="gridCheck4">
              Hiring & Recruiting
            </label>
          </div>
        </div>
        <div class="col-6 firstName">
          <label for="firstName" class="form-label appCheckLabel"
            >List up to three roles that you partake in
          </label>
          <input
            type="text"
            class="form-control"
            placeholder="e.g. Director, Cinematographer, Editor"
            aria-label="First name"
          />
        </div>
        <div class="row">
          <div class="col-md-6">
            <select id="inputState" class="form-select selectHearAbout">
              <option selected disabled>How did you hear about us?</option>
              <option value="Referral" aria-selected="true">Referral</option>
              <option value="Search Engine" aria-selected="false">
                Search Engine
              </option>
              <option value="Social Media" aria-selected="false">
                Social Media
              </option>
              <option value="Sponsored Content" aria-selected="false">
                Sponsored Content
              </option>
            </select>
          </div>
        </div>
        <div class="row">
          <div class="col-md-6 mt-5">
            <div class="form-check">
              <input
                class="form-check-input"
                type="checkbox"
                value=""
                id="flexTermService"
              />
              <label class="checked" for="flexTermService"></label>

              <label class="form-check-label" for="flexTermService">
                I agree to the terms & conditions
                <a href="#">Views terms of use</a>
              </label>
            </div>
          </div>
        </div>
        <div class="row">
          <div class="col-md-6 mt-4">
            <div class="form-check">
              <input
                class="form-check-input"
                type="checkbox"
                value=""
                id="flexNewsLetter"
              />
              <label class="checked" for="flexNewsLetter"></label>

              <label class="form-check-label" for="flexNewsLetter">
                I want to subscribe to the newsletter.
              </label>
            </div>
          </div>
        </div>

        <div class="col-12 text-center">
          <div class="btn-section">
            <div class="button">join the waitlist</div>
          </div>
        </div>
      </form>
    </div>
    <div class="social">
      <img :src="TikTok" alt="TikTok" width="38" height="38" />
      <img :src="Twitter" alt="Twitter" width="38" height="38" />
    </div>
    <div class="footerLink">
      <div>Terms & Conditions</div>
      <div class="divider">|</div>
      <div>Privacy Policy</div>
      <div class="divider">|</div>
      <div>CCPA</div>
    </div>
  </div>
</template>

<script setup>
import TikTok from "~/src/assets/images/tiktokWhite.svg";
import Twitter from "~/src/assets/images/twitterWhite.svg";
</script>

<style lang="scss" scoped>
.community-section {
  display: flex;
  justify-content: center;
  align-items: center;
  flex-direction: column;
  box-sizing: border-box;
  padding: 8rem 2rem 0rem 2rem;
  gap: 1rem;
  background: radial-gradient(
      circle at 23.75% 3.3333333333333335%,
      #141414 0%,
      43%,
      rgba(20, 20, 20, 0) 100%
    ),
    radial-gradient(
      circle at 47.083333333333336% 0.8333333333333334%,
      #141414 0%,
      36%,
      rgba(20, 20, 20, 0) 100%
    ),
    radial-gradient(
      circle at 100% 100%,
      #262626 0%,
      50%,
      rgba(38, 38, 38, 0) 100%
    ),
    radial-gradient(
      circle at 52.083333333333336% 55.833333333333336%,
      #2998ff 0%,
      50%,
      rgba(41, 152, 255, 0) 100%
    ),
    radial-gradient(
      circle at 6.503906249999999% 88.037109375%,
      rgba(20, 20, 20, 0.99) 0%,
      50%,
      rgba(20, 20, 20, 0) 100%
    ),
    radial-gradient(
      circle at 0% 0%,
      rgba(20, 20, 20, 0.83) 0%,
      60%,
      rgba(20, 20, 20, 0) 100%
    ),
    radial-gradient(
      circle at 82.91666666666667% 2.5%,
      #141414 0%,
      60%,
      rgba(20, 20, 20, 0) 100%
    ),
    radial-gradient(
      circle at 48.9013671875% 49.521484375%,
      #ffffff 0%,
      100%,
      rgba(255, 255, 255, 0) 100%
    );

  .heading {
    max-width: 1200px;
    font-size: 60px;
    color: #ffffff;
    font-weight: 400;

    line-height: normal;
    font-style: normal;
    @media screen and (max-width: 768px) {
      font-size: 35px;
      text-align: center;
    }
    span {
      font-weight: 600;
      font-style: italic;
    }
  }
  .para {
    max-width: 1200px;
    font-size: 18px;
    line-height: normal;
    font-weight: 400;
    width: 70%;
    letter-spacing: normal;
    margin: auto;
    text-align: center;
    padding-bottom: 75px;
    color: #8f9fb8;
    @media screen and (max-width: 768px) {
      font-size: 14px;
      width: 100%;
    }
    span {
      font-style: italic;
      font-weight: bold;
    }
  }
  .card-wrapper {
    max-width: 1200px;
    display: flex;
    flex-wrap: wrap;
    width: 80%;
    gap: 2rem;
    margin-left: 0px;
    @media screen and (max-width: 768px) {
      flex-direction: column;
      width: 100%;
    }
    .card-body {
      width: 40%;
      border-radius: 35px;
      padding: 30px;
      border: 0px;
      box-sizing: border-box;
      text-align: center;
      box-shadow: 4.59px 5.28px 35px 0px rgba(0, 0, 0, 0.89);
      background: transparent;
      transition: all 0.2s ease-in;
      @media screen and (max-width: 768px) {
        width: 100%;
      }

      &:hover {
        transform: scale(1.05);
      }
      .card-heading {
        font-size: 21px;
        color: #f7f8fb;
        font-style: normal;
        line-height: normal;
        letter-spacing: normal;
        font-weight: 500;
        margin-bottom: 10px;
      }
      .card-para {
        font-size: 16px;
        color: #cdd5e1;
        font-style: normal;
        line-height: normal;
        letter-spacing: normal;
        font-weight: 400;
        span {
          font-weight: bold;
          font-style: italic;
        }
      }
    }
  }
  .party-heading {
    font-size: 50px;
    font-weight: 400;
    margin-top: 75px;
    font-style: normal;
    color: #ffffff;
  }

  .form-wrapper {
    max-width: 1200px;

    width: 70%;
    margin: auto;
    label {
      color: #ffffff;
      font-size: 13px;
    }
    p {
      color: #ffffff;
      font-size: 13px;
    }
    .firstName {
      input {
        background: transparent;
        border: none;
        border-bottom: 2px solid white;
        outline: none;
        border-radius: 0px;
        &:focus {
          border: none;
          box-shadow: none;
          border-bottom: 2px solid rgb(41, 152, 255);
          outline: none;
        }
        &:hover {
          outline: none;
        }
      }
    }
    .lastName {
      input {
        background: transparent;
        border: none;
        border-bottom: 2px solid white;
        outline: none;
        border-radius: 0px;
        &:focus {
          border: none;
          box-shadow: none;
          border-bottom: 2px solid rgb(41, 152, 255);
          outline: none;
        }
        &:hover {
          outline: none;
        }
      }
    }
    .email {
      input {
        background: transparent;
        border: none;
        font-size: 13px;
        border-bottom: 2px solid white;
        outline: none;
        border-radius: 0px;
        &:focus {
          border: none;
          box-shadow: none;
          border-bottom: 2px solid rgb(41, 152, 255);
          outline: none;
        }
        &:hover {
          outline: none;
        }
      }
    }
    .appCheckLabel {
      font-style: italic;
      color: #ffffff;
    }
    .form-check {
      display: flex;
      gap: 10px;
      padding: 0px;
      align-items: center;
      label {
        font-size: 16px;
      }
    }
    .form-check-input {
      display: none;
    }
    .checked {
      width: 16px;
      height: 16px;
      padding: 2px;
      border: 1px solid white;
      justify-content: center;
      align-items: center;
      display: flex;
    }
    .form-check-input:checked + .checked {
      background-image: url("../../src/assets/images/checked.svg");
      background-repeat: no-repeat;
      border: 1px solid #3578f8;
    }
    .industryChecked {
      width: 16px;
      height: 16px;
      padding: 2px;
      border: 1px solid white;
      border-radius: 50%;
      justify-content: center;
      align-items: center;
      display: flex;
    }
    .form-check-input:checked + .industryChecked {
      border: 1px solid #3578f8;
      position: relative;
      &::after {
        position: absolute;
        content: "";
        height: 50%;
        width: 50%;
        border-radius: 50%;
        top: 25.5%;
        left: 25.7%;
        background-color: #3578f8;
        z-index: 1;
      }
    }
    .selectHearAbout {
      background: transparent;
      color: #ffffff;
      margin-top: 3rem;
      border: none;
      font-size: 13px;
      border-radius: 0px;
      border-bottom: 2px solid white;
      box-shadow: none;
      option {
        color: #141414;
      }
    }
    .btn-section {
      display: flex;
      justify-content: center;
      align-items: center;
      .button {
        margin: 4rem 0rem 0rem 0rem;
        color: white;
        border-radius: 4px;
        background: repeat padding-box border-box 0% 0% / auto auto scroll
          linear-gradient(
            90deg,
            rgba(41, 152, 255, 0.31) 10%,
            rgba(41, 152, 255, 0.13) 50%,
            rgba(41, 152, 255, 0.27) 84%
          );
        border: 1px solid #2998ff;
        height: 53px;
        min-width: 270px;
        font-weight: normal;
        font-style: normal;
        font-size: 16px;
        font-weight: 500;
        display: flex;
        letter-spacing: 0em;
        text-transform: uppercase;
        align-items: center;
        justify-content: center;
        transition: all 0.3s ease-in-out 0s, visibility 0s;
        padding: 0px 3rem;

        cursor: pointer;
      }

      .button:hover {
        background: repeat padding-box border-box 0% 0% / auto auto scroll
          linear-gradient(
            134deg,
            rgba(41, 152, 255, 0.51) 0%,
            rgba(41, 152, 255, 0.6) 46%,
            rgba(41, 152, 255, 0.6) 100%
          );
      }
    }
  }
  .social {
    display: flex;
    gap: 0.5rem;
    padding: 3rem 0rem;
  }

  .footerLink {
    padding: 1rem 0rem;
    display: flex;
    justify-content: center;
    align-items: center;
    gap: 1.2rem;
    color: #bfbfbf;
    font-size: 14px;
    .divider {
      font-size: 2rem;
      font-weight: 100;
    }
  }
}
</style>
