<!-- <!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="style.css">
    <title>Document</title>
</head> -->
<!-- <body> -->

<template>
    <p>{{ msg }}</p>
    <nav>
        <div class="nav-container">
            <div class="nav-img">
                <img src="./assets/whiteLogo.png" alt="whiteLogo">
            </div>
            <div class="nav-one">
                <ul>
                    <!-- <li><img src="./assets/whiteLogo.png" alt="whiteLogo"></li> -->
                    <li><a href="vale.ng/">Home</a></li>
                    <li><a href="vale.ng/about">About Us</a></li>
                    <li><a href="vale.ng/faq">FAQ</a></li>
                    <li><a href="https://loans.valefinance.com/">Loan</a></li>
                    <li><a href="#">Blog</a></li>
                    <li><a href="#">Interest Calculator</a></li>
                </ul>
            </div>
            <div class="nav-two">
                <ul>
                    <li><a href="/login">Login</a></li>
                    <li><a href="/signup">Sign Up</a></li>
                </ul>
            </div>
        </div>
    </nav>

    <section class="referrals">
        <div class="container">
            <div class="text_section">
                <h1>The Bank That Truly Pays You</h1>
                <ul>
                    <li>Savings</li>
                    <li>Payment</li>
                    <li>Loans</li>
                </ul>
                <h6>Our investment products and savings plans help
                    everyday people build and preserve wealth effortlessly.
                </h6>
                <!-- <p> Licensed by the Central Bank Of Nigeria</p> -->
                <ul>
                    <li>Licensed by the Central Bank Of Nigeria</li>
                    <li><img src="./assets/cbnLogo.81ecf24.svg" alt="cbn"></li>
                </ul>
                <ul class="os">
                    <li><img src="./assets/google-play-white-outline.de145c1.svg" alt="android"></li>
                    <li><img src="./assets/apple-store-white-outline.891728c.svg" alt="ios"></li>
                </ul>
            </div>
            <div class="image_section">
                <img src="./assets/picture_one.png" alt="mobile_app">
            </div>
        </div>
    </section>

    <section class="products">
        <h3 class="benefits">
            With Vale You Have Numerous Benefits
        </h3>
        <div class="security">
            <div class="image_s">
                <img src="./assets/security.png" alt="security">
            </div>
            <div class="text_s">
                <h5>
                    Smart and reliable security to protect your fund
                </h5>
                <p>
                    Vale is secured by 256 bits SSL security encryption to ensure that your information is safe and completely protected from fraud. Also, our payment processors are PCIDSS compliant to ensure optimum security of your data electronically.
                </p>
            </div>
        </div>
        <div class="savings">
            <div class="image_s">
                <img src="./assets/smart-save.png" alt="">
            </div>
            <div class="text_s">
                <h5>
                    Save smarter and earn huge returns without stress
                </h5>
                <p>
                    Savings could be difficult, but Vale makes it easy. You do not have to worry about how to save. We provide you with numerous savings plans customized to your lifestyle while offering irresistible returns.
                </p>
            </div>
        </div>
        <div class="loans">
            <div class="image_s">
                <img src="./assets/money-bag.png" alt="">
            </div>
            <div class="text_s">
                <h5>
                    Getting a loan has always been very easy with Vale
                </h5>
                <p>
                    It is no longer necessary to liquidate your savings or investments when you get cash trapped. Vale offers flexible and easy-to-repay overdraft loans on your account.
                </p>
            </div>
        </div>
        <div class="wallet">
            <div class="image_s">
                <img src="./assets/pay-bills.png" alt="">
            </div>
            <div class="text_s">
                <h5>
                    Pay your bills and manage your expenses from Vale
                </h5>
                <p>
                    Vale makes it easy for you to pay your utilities, buy airtime, mobile data, pay-tv subscription while still tracking your expenses..
                </p>
            </div>
        </div>
        <div class="investment">
            <div class="image_s">
                <img src="./assets/investment-decision.png" alt="">
            </div>
            <div class="text_s">
                <h5 >
                    Make smart investment decisions on the go and put your money to work.
                </h5>
                <p>
                    Vale provides you with a Robo-Advisor that helps you invest well, save smart, and achieve your goals using Machine Learning (ML) analysis of the market trends. These investments guarantee good returns for you in growing your money.
                </p>
            </div>
        </div>
        <div class="benefit">
            <h3>
                Meet Vale Products Tailored for you
            </h3>
        </div>
        <div class="target">
            <div class="target_one">
                <div class="target2">
                    <div class="target1">
                        <img src="./assets/target-plan-info.aab7fcb.svg" alt="info">
                    </div>
                    <div>
                        <img src="./assets/target-icon.2592d90.svg" alt="n-icon">
                        <h5>My target</h5>
                        <p>
                            Save towards targets and earn up to 9% interest per annum within a defined period of time. Target savings can be done one-off or on a daily, weekly, monthly, or quarterly basis, in line with your unique individual or business goals.
                        </p>
                    </div>

                    <div class="target3">
                        <img src="./assets/target-plan-success.6a63ad4.svg" alt="success">
                    </div>
                </div>
            </div>
        </div>
        <div class="vault">
            <div class="target_two">
                <div class="target5">
                    <div class="target4">
                        <img src="./assets/empty-vault-plan.c0da9b1.svg" alt="">
                    </div>
                    <div>
                        <img src="./assets/vault-icon.fbeafb5.svg" alt="">
                        <h5>My Vault</h5>
                        <p>
                            Invest and earn up to 16% interest per annum, depending on your investment amount. With our vault plan, you can earn interest upfront. This plan allows you to lock your money in and grow it. You can either choose to reinvest the investment or liquidate it at the end of the set date (tenor).
                        </p>
                        <p>
                            Note: Your investment cannot be terminated before maturity as you have received your interest upfront.
                        </p>
                    </div>
                    <div class="target6">
                        <img src="./assets/vault-plan-info.ccf5b3c.svg" alt="">
                    </div>
                </div>
            </div>
        </div>
    </section>

    <section class="feature-wrapper">
        <div class="feature">
            <h4>
                As Featured In
            </h4>
        </div>
        <div class="grid-wrapper">
            <div class="grid">
                <img src="./assets/featured/techpoint.4a60ee7.svg" alt="Techpoint">
            </div>
            <div class="grid">
                <img src="./assets/featured/punch.60b4c4c.svg" alt="Punch">
            </div>
            <div class="grid">
                <img src="./assets/featured/nairametric.7c03850.svg" alt="Nairametric">
            </div>
        </div>
    </section>

    <div class="testimonial">
        <div class="header-wrapper">
            <h1 class="users">
                Our users are in love with us
            </h1>
            <p>
                Since launch we have helped people from all works of life grow and achieve their personal financial goals.
            </p>
        </div>
        <div class="container-testimonial">
            <div class="testimonial-card">
                <div class="testimonial-content">
                    Vale is awesome! It's secure, safe and smart when it comes to handling your finances. I love this app and recommend it to my friends and anyone who cares to manage and grow their finances with the much needed confidence and discipline it requires. Keep up the good work!
                </div>
                <div class="name">
                    Moses Ekeruo
                </div>
            </div>
            <div class="testimonial-card">
                <div class="testimonial-content">
                    This app is more than great, especially their customer service that respond fast and at last solving someone’s problem, I recommended it. It’s awesome.
                </div>
                <div class="name">
                    Chukwudire Nwajiaku
                </div>
            </div>
            <div class="testimonial-card">
                <div class="testimonial-content">
                    Good and reliable. I make complaint here like 30 minutes ago and it has been rectified. Good customer service.
                </div>
                <div class="name">
                    Ayano Aanuoluwapo
                </div>
            </div>
        </div>
    </div>

    <div class="referral-section">
        <div class="grid_one">
            <h2>
                Refer friends and earn money
            </h2>
            <p>
                When you refer a friend, you get N500 after the person you refer completes the registration process and makes a minimum deposit of N1000.
            </p>
            <h4 class="title">
                How does it work?
            </h4>
            <div class="steps">
                <h3>
                    Step One
                </h3>
                <ul>
                    <li>
                        Login to your Vale account
                    </li>
                    <li>
                        Click on “More” icon at the bottom right of your screen, then click on “Referral”.
                    </li>
                    <li>
                        Copy your referral link and share it with family and friends!
                    </li>
                </ul>
            </div>
            <div class="steps">
                <h3>
                    Step Two
                </h3>
                <ul>
                    <li>
                        Get your referred user to complete KYC, and
                    </li>
                    <li>
                        Fund wallet with a minimum of N1,000.
                    </li>
                </ul>
            </div>
            <div class="steps">
                <h3>
                    Step Three
                </h3>
                <ul>
                    <li>
                        As soon as requirements are met, your wallet will be credited with 500 Naira!
                    </li>
                </ul>
            </div>
        </div>
        <div class="grid_twoo">
            <img src="./assets/referrals.png" alt="">
        </div>
    </div>

    <section id="testimonies">
        <div class="card-wrapper">
            <div class="grid_one">
                <img src="./assets/mobile-app.png" alt="Vale_App">
            </div>
            <div class="grid_two">
                <div class="image">
                    <img src="./assets/bg12.2f312b9.png" alt="">
                    <h4> Join Vale Today </h4>
                    <p>And start your journey to financial freedom</p>
                </div>
                <div class="phones">
                    <ul>
                        <li>
                            <img src="./assets/google-play-blue-outline_android.png" alt="Google Play Badge">
                        </li>
                        <li>
                            <img src="./assets/apple-store-blue-outline.795c738.png" alt="Apple Play Badge">
                        </li>
                    </ul>
                </div>
            </div>
        </div>
    </section>

    <section class="partners">
        <div class="partner_text">
            <p>
                Our Partners
            </p>
        </div>

        <div class="grid-wrapper">
            <div class="grid_one">
                <img src="./assets/partners/flutterwave-logo.d8a3103.svg" alt="Flutterwave">
            </div>
            <div class="grid_two">
                <img src="./assets/partners/interswitch-logo.6854912.svg" alt="Interswitch">
            </div>
            <div class="grid_three">
                <img src="./assets/partners/providus-logo.8ee7133.svg" alt="Paystack">
            </div>
            <div class="grid_four">
                <img src="./assets/partners/anchora.7830a5f.svg" alt="Vale Finance">
            </div>
        </div>
    </section>

    <footer>
        <div class="containerTwo">
            <div class="white-logo">
                <img src="./assets/whiteLogo.png" alt="">
                <h6>
                    Savings, Payments, Loans
                </h6>
            </div>
            <div class="quick_links">
                <h6>Quick Link</h6>
                <ul>
                    <li>Our story</li>
                    <li>FAQs</li>
                    <li>Media</li>
                </ul>
            </div>
            <div class="legals">
                <h6>Legals</h6>
                <ul>
                    <li>Terms and Conditions</li>
                    <li>Privacy Policy </li>
                </ul>
            </div>
            <div class="contact">
                <h6>Contact Us</h6>
                <div class="icon">
                    <ul>
                        <li><img src="./assets/footer/home_button.svg" alt="home_button"></li>
                        <li> UAC Building, 1-5 Odunlami St, <br> Lagos Island, Lagos</li>
                    </ul>
                </div>
                <div class="icon">
                    <ul>
                        <li><img src="./assets/footer/phone_icon.svg" alt="phone_icon"></li>
                        <li>+2349062818090</li>
                    </ul>
                </div>
                <div class="icon">
                    <ul>
                        <li><img src="./assets/footer/mail_button.svg" alt="mail_button"></li>
                        <li>hello@vale.ng</li>
                    </ul>
                </div>
                <div class="icon">
                    <ul>
                        <li><a href="https://www.linkedin.com/company/74031606/admin/"><img src="./assets/footer/linkedIn.svg" alt="linkedIn"></a></li>
                        <li><a href="https://web.facebook.com/fundbeang"><img src="./assets/footer/facebook.svg" alt="facebook"></a></li>
                        <li><a href="https://www.instagram.com/getvaleapp/"><img src="./assets/footer/instagram-alt.28e2352.svg" alt="instagram"></a></li>
                        <li><a href="https://www.twitter.com/getvaleapp"><img src="./assets/footer/twitter.svg" alt="twitter"></a></li>
                    </ul>
                </div>
                <div>
                    <p><strong>Whistle Blower</strong> <br> whistleblow@valefinance.com</p>
                </div>
            </div>
        </div>
        <div class="final">
            <br> <hr> <br>
            <p id="footer">
                Vale is a Mobile Banking solution powered by Vale Finance Limited – a finance Company duly regulated by the Central Bank of Nigeria (CBN). Dollar investments are offered under a reseller partnership with Anchoria Asset Management Limited – a SEC-licensed asset management company. Deposit accounts are issued and managed by CBN-licensed deposit money banks
            <br><br>
                © 2023 powered by Vale Finance Limited
            </p>
        </div>
    </footer>
</template>

<script>
export default {
  name: 'Homepage',
  props: { msg: String }
}
</script>

<style scoped> @import "./style.css"; </style>
<!-- </body>
</html> -->