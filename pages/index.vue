<template>
  <v-layout column justify-center align-center dark>
   <nav>
        <img src="@/assets/logo.png" class="logo" alt="">
        <span class="login">LOGIN</span>
    </nav>

      <!-- Background-Main -->
    <div class="container-fluid" id="home">
        <div class="row flex-md-row flex-column-reverse">
            <div class="col-md-5 col-12 slider">
                <h1 class="d-md-block d-none">Deine Webseite für Jobs</h1>
                <!-- Carousel Wrapper -->
                <div id="carousel-example-2" class="carousel slide carousel-fade" data-ride="carousel">
                    <ol class="carousel-indicators">
                        <li data-target="#carousel-example-2" data-slide-to="0" class="active"></li>
                        <li data-target="#carousel-example-2" data-slide-to="1"></li>
                        <li data-target="#carousel-example-2" data-slide-to="2"></li>
                    </ol>
                    <div class="carousel-inner" role="listbox">
                        <div class="carousel-item active">
                            <div class="view">
                                <div class="ImgGroup">
                                    <img src="@/assets/slide1img1.png" class="small" alt="">
                                    <div class="ImgContainer">
                                        <img src="@/assets/slide1img2.png" alt="">
                                    </div>
                                </div>
                                <div class="Captions d-flex ">
                                    <h5>Markus H.</h5>
                                    <span>Brandschutz Consulting</span>
                                    <p>Tempi ermöglicht uns eine schnelle und einfache Abwicklung auf der Suche nach
                                        neuen Mitarbeiter.</p>
                                </div>
                            </div>
                        </div>
                        <div class="carousel-item">
                            <div class="view">
                                <div class="ImgGroup">
                                    <div class="ImgContainer">
                                        <img src="@/assets/slide2img2.png" alt="">
                                    </div>
                                </div>
                                <div class="Captions d-flex ">
                                    <h5>Gianluca F. </h5>
                                    <span>Arbeitnehmer</span>
                                    <p>Einen neuen Job auf Tempi zu finden war für mich sehr einfach.</p>
                                </div>
                            </div>
                        </div>
                        <div class="carousel-item">
                            <div class="view">
                                <div class="ImgGroup">
                                    <img src="@/assets/slide3img1.png" class="small" alt="">
                                    <div class="ImgContainer">
                                        <img src="@/assets/slide3img2.png" alt="">
                                    </div>
                                </div>
                                <div class="Captions d-flex ">
                                    <h5>Robert Mosser-Waller</h5>
                                    <span>Gesamtschulleitung Pestalozzi Schulen</span>
                                    <p>Dank Tempi können wir schnell und gezielt Mitarbeiter akquirieren.</p>
                                </div>
                            </div>
                        </div>
                    </div>
                </div>
                <!--/.Carousel Wrapper-->
            </div>
            <div class="col-md-4 my-2 col-12 form">
                <form>
                    <h5>Ich möchte mich jetzt kostenlos registrieren</h5>
                    <span>Registrieren Sie sich mit Ihrem Social Media Konto an.</span>
                    <button><i class="fa fa-google"></i> mit google registrieren</button>
                    <button><i class="fa fa-facebook"></i> mit fACEBOOK registrieren</button>
                    <span>oder registrieren Sie sich mit Ihrer E-Mail-Adresse an.</span>
                    <input type="text" placeholder="Vorname">
                    <input type="text" placeholder="Familienname">
                    <input type="text" placeholder="Private E-Mail-Adresse">
                    <footer>
                        <span class="footer">
                            Sie erklären sich mit der Nutzervereinbarung, der Datenschutzrichtlinie und der
                            Cookie-Richtlinie von TEMPI einverstanden.
                        </span>

                        <button class="submit">Kostenlos Registrieren</button>
                        <span>überspringen</span>
                    </footer>
                </form>
            </div>
            <h1 class="d-block d-md-none heading">Deine Webseite für Jobs</h1>

        </div>
    </div>


        <!-- job-body -->
    <div class="container" id="Body">
        <div class="row">
            <div class="col-12 content">
                <div class="Cover d-md-block d-none">
                    <img src="@/assets/cover1.png" alt="">
                    <p>Crewmitarbeiter/IN</p>
                </div>
                <div class="Content">
                    <div class="Brand">
                        <div class="logo">
                            <img src="@/assets/brand1.png" alt="">
                        </div>
                        <div class="text">
                            <span class="d-md-none d-block">Crewmitarbeiter/IN</span>
                            <p>McDonald's</p>
                            <p>8105 Regensdorf</p>
                        </div>
                    </div>
                    <span>anschauen & bewerben</span>
                </div>
            </div>

            <div class="col-12 content mt-3">
                <div class="Cover d-md-block d-none">
                    <img src="@/assets/cover2.png" alt="">
                    <p>Senior Accountant</p>
                </div>
                <div class="Content">
                    <div class="Brand">
                        <div class="logo">
                            <img src="@/assets/brand2.png" alt="">
                        </div>
                        <div class="text">
                            <span class="d-md-none d-block">Senior Accountant</span>
                            <p>LIPO Einrichtungsmärkte AG</p>
                            <p>4133 Pratteln</p>
                        </div>
                    </div>
                    <span>anschauen & bewerben</span>
                </div>
            </div>
            <div class="col-12 content mt-3">
                <div class="Cover d-md-block d-none">
                    <img src="@/assets/cover3.png" alt="">
                    <p>Hauswart (m/w)</p>
                </div>
                <div class="Content">
                    <div class="Brand">
                        <div class="logo">
                            <img src="@/assets/brand3.png" alt="">
                        </div>
                        <div class="text">
                            <span class="d-md-none d-block">Hauswart (m/w)</span>
                            <p>ISS Facility Services AG</p>
                            <p>4126 Bettingen</p>
                        </div>
                    </div>
                    <span>anschauen & bewerben</span>
                </div>
            </div>
            <div class="col-12 btns my-3">
                <button>mehr Jobs</button>
            </div>
        </div>
    </div>



     




<Jobs/>
<FooterTop/>
<FooterBottom/>

  </v-layout>
</template>

<script>

import Carousels from '@/components/Carousels';
import AboutUs from '@/components/AboutUs';
import FooterTop from '@/components/FooterTop';
import FooterBottom from '@/components/FooterBottom';
import Jobs from '@/components/Jobs';



export default {
  components:{
    Carousels,
    AboutUs,
    Jobs,
    FooterTop,
    FooterBottom

  }
}
</script>
