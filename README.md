import React from 'react'

const Hero = () => {
    return (
        <div id="hero-section" class="bg-light-purpple position-relative" >
            <div class="container">
                <div class="row">
                    <div class="col-6 left-hero pr-4 d-flex align-items-center">
                        <div class="box">
                            <h1 class="heading-style" style="color: black;"> Sewa dan Rental Mobil Terbaik di kawasan Bandar Lampung</h1>
                            <p>class = "Selamat datang di Binar Car Rental, Kami menyediakan mobil kualitas terbaik dengan harga terjangkau. Selalu siap melayani kebutuhanmu untuk sewa mobil selama 24 jam.</p> 
                                <a class="btn btn-green mt-3 text-light" href="#">Mulai Sewa Mobil</a>
                        </div>
                    </div>
                    <div class="col-lg-6 right-hero"></div>
                    <img class="car img-fluid" src="mobilporject.jpg" alt="car"/>
                    <div />
                </div>
            </div>
    )
}
