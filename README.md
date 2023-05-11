# Nabiclothin.github.io
*{
margin: 0;
padding: 0;
box-sizing: border-box;
scroll-behavior: smooth;
font-family: 'Jost', sans-serif;
list-style: none;
text-decoration: none;
}
header{
    position: fixed;
    width: 100%;
top: 0;
right: 0;
z-index: 1000;
display: flex;
align-items: center;
justify-content: space-between;
padding: 20px 10%;

}

.logo img{
max-width: 220px;
height: 50;
}
.navmenu{
    display: flex;
}

.navmenu a{
color: #2c2c2c;
font-size: 16px;
text-transform:capitalize;
padding: 10px 20px;
font-weight: 400;
transition: all .42s ease;
}
.navmenu a:hover{
    color: #4685e3;
}
.nav-icon{
display: flex;
align-items: center;
}

.nav-icon i{
    margin-right: 20px;
    color: #2c2c2c;
    font-size: 25px;
    font-weight: 400;
    transition: all .42s ease;
}
.nav-icon i:hover{
transform: scale(1.1);
color: #4685e3;

}
#menu-icon{
    font-size: 35px;
    color: #2c2c2c;
    z-index: 10001;
    cursor: pointer;
}
section{
    padding: 8% 10%;
}
.main-home{
    width: 100%;
    height: 100vh;
    background-image: url('../My\ project-1\ \(1\).png');
    background-position: center;
    background-size: cover;
    display: grid;
    grid-template-columns: repeat(1, 1fr);
    align-items: center;

}
.main-text h5{
    color: white;
    font-size: 16px;
    text-transform: capitalize;
    font-weight:500 ;
}
.main-text h1{
    color: white;
    font-size: 65px;
    text-transform: capitalize;
    line-height: 1.1;
    font-weight: 600;
    margin: 6px 0 10px;
}
.main-text p{
    color: white;
    font-size: 20px;
    font-style: italic;
    margin-bottom: 20px;
}
.main-btn{
    display: inline-block;
    color: white;
    font-size: 16px;
    font-weight: 500;
    text-transform: capitalize;
    border: 2px solid #111;
    padding: 12px 25px;
    transition: all .42s ease;
}
.main-btn:hover{
    background-color: #000;
    color: #fff;
}
.main-btn i{
    vertical-align: middle ;
}
.down-arrow{
    position: absolute;
    top: 85%;
    right: 11%;
}
.down i{
    font-size: 30px;
    color: #2c2c2c;
    border: 2px solid #2c2c2c;
    border-radius: 50px;
    padding: 12px 12px;
}
.down i:hover{
    background-color: #2c2c2c;
    color: #fff;
    transition: all .42s ease;
}

header.sticky{
    background: #fff    ;
    padding: 20px 10%;
    box-shadow: 0px 0px 10px  rgb(0 0 0 / 10%);
}
.center-text h2{
    color: #111;
    font-size: 28px;
    text-transform: capitalize;
    text-align: center;
    margin-bottom: 30px;
}
.center-text span{
    color: #4685e3;
}
.products{
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(260px, auto));
    gap: 2rem;
}
.row{
    position: relative;
    transition: all .40s;
}
.row img{
    width: 100%;
    height: auto;
    transition: all .40s;
}
.row img:hover{
    transform: scale(0.9);
}
.product-text h5{
    position: absolute;
    top: 13px;
    left: 13px;
    color: #fff;
    font-size: 12px;
    font-weight: 500;
    text-transform: uppercase;
    background-color: #4685e3;
    padding: 3px 10px;
    border-radius: 2px;
}
.heart-icon{
    position: absolute;
    right: 0;
    font-size: 20px;
}
.heart-icon:hover{
    color: #4685e3;
}
.patting i{
    color: #ff8c00;
    font-size: 18px;
}
.price h4{
    color: #111;
    font-size: 16px;
    text-transform: capitalize;
    font-weight: 400;
}
.price p{
    color: #151515;
    font-size: 14px;
    font-weight: 600;
}
.client-reviews{
    background-color: #9dbcec;
}
.reviews{
    text-align: center;
}
.reviews h3{
    color: #111;
    font-size: 25px;
    text-transform: capitalize;
    text-align: center;
    font-weight: 700;
}
.reviews img{
    width: 100px;
    height: auto;
    border-radius: 50px;
    margin: 10px 0;
}
.reviews p{
    color: #000;
    font-size: 16px;
    font-weight: 400;
    line-height: 25px;
    margin-bottom: 10px;
}
.reviews h2{
    font-size: 22px;
    color: #000;
    font-weight: 400;
    text-transform: capitalize;
    margin-bottom: 2px;
}
.up-center-text span{
    color: #4685e3;
}
.up-center-text h2{
    text-align: center;
    color: #111;
    font-size: 25px;
    text-transform: capitalize;
    font-weight: 700;
    margin-bottom: 30px;
}
.cart img{
    width: 380px;
    height: auto;
    border-radius: 5px;
}
.update-cart{
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(380px, auto));
    gap: 1rem;
}
.cart h5{
    color: #636872;
    font-size: 14px;
    text-transform: capitalize;
    font-weight: 500;
}
.cart h4{
    color: #111;
    font-size: 18px;
    font-weight: 600;
}
.cart p{
    color: #707070;
    font-size: 15px;
    max-width: 380px;
    line-height: 25px;
    margin-bottom: 12px;
}
.cart h6{
    color: #151515;
    font-size: 14px;
    font-weight: 500;
}
.contact{
    background-color: #f3f4f6;
}
.contact-info{
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(160px, auto));
    gap: 3rem;
}
.first-info img{
    width: 50px;
    height: auto;
}
.contact-info h4{
    color: #212529;
    font-size: 14px;
    text-transform: uppercase;
    margin-bottom: 10px;
}
.contact-info p{
    color: #565656;
    font-size: 14px;
    font-weight: 400;
    text-transform: capitalize;
    line-height: 1.5;
    margin-bottom: 10px;
    cursor: pointer;
    transition: all .42s;
}
.contact-info p:hover{
    color: #4685e3;
}
.social-icon i{
    color: #565656;
    margin-right: 10px;
    font-size: 20px;
    transition: all .42s;
}
.social-icon i:hover{
    transform: scale(1.3);
}
.end-text{
    background-color: #edfff1;
    text-align: center;
    padding: 20px;
}
.end-text p{
    color: #111;
    text-transform: capitalize;
}

@media(max-width:890px){
    header{
        padding: 20px 3%;
        transition: .4s;
    }
}
@media(max-width:630px){
    .main-text h1{
        font-size: 50px;
        transition: .4s;
    }
    .main-text p{
        font-size: 50px;
        transition: .4s;
    }
    .main-btn{
        padding: 10px 20px;
        transition: .4s;
    }
}
@media(max-width:750px){
    .navmenu{
        position: absolute;
        top: 100%;
        right:-100%;
        width: 300px;
        height: 130vh;
        background: #edfff1;
        display: flex;
        flex-direction: column;
        align-items: center;
        padding: 120px 30px;
        transition: all .42s;
    }
    .navmenu a{
        display: block;
        margin: 18px 0;
    }
    .navmenu.open{
        right: 0;
    }
}
