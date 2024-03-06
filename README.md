# GIIAN_TEST_PJ 

https://emfagroup.larksuite.com/docx/BWO3d4HEQooPgUxUDvounQbPsib


########CSS_part########
.product__List{
    display: grid;
    grid-template-columns: repeat(4,1fr);
    gap: 10px;

    list-style: none;
    height: 1920px;
    /* width: 1080px; */
    justify-content: center;
    align-items: center;
}
.product__item{
    background: transparent
}
.product-item__card{
    display: grid;
    /* grid-template-rows: max-content; */
    background: transparent;
    border: 1px solid transparent;
    border-radius: 5px;
    overflow: hidden;
}
.product-item__card:hover{
    /* display: grid; */
    /* grid-template-rows: max-content; */
    background: white;
    border: 1px solid white;
    /* border-radius: 5px; */
    /* overflow: hidden; */
}

.product-item__img{
    width: 100%;
    aspect-ratio: 1/1;
}
.product-itemCard-desc{
    margin-top: 10px;
}
.product-itemCard-desc-type{
    text-transform: uppercase;
    border-radius: 4px;
    background: #b93f3f;
    color: white;
    padding: 4px;
    margin-left: 1px;
    margin-right: 8px;

    font-size: 12px;

    /* display:flex; */
    justify-content:center;
    align-items: center;
}
.product-itemCard-desc-text{
        /* display:flex; */
    justify-content:center;
    align-items: center;

    font-size: 12px;
}
.product-itemCard-purchase{
    display:flex;
    justify-content:space-between;
    align-items: center;
    margin-top: 10px;
    padding: 0;
}
.product-itemCard-purchase-price{
    margin-left: 1px;
    display:flex;
    align-items: center;

    font-size: 12px;
    font-weight: bold;
}
.product-itemCard-purchase-add{
    margin-right: 1px;
    margin-bottom: 1px;
    border-radius: 20px;
    border: 1px solid #000;
    display:flex;
    align-items: flex-end;
    padding: 2px 12px;
}
.product-itemCard-purchase-add-img{
    display:flex;
    align-items: center;
    justify-content:center;
    color: #000;
}


########HTML_part########
    <div class="wrapper">
        <div class="product-container">
            <ul class="product__List">
                <li class="product__item">
                    <div class="product-item__card">
                        <a href="#" class="product-item-detail">
                            <img src="/?"class="product-item__img">
                        </a>
                        <div class="product-itemCard-desc">
                            <span class="product-itemCard-desc-type">New</span>
                            <span class="product-itemCard-desc-text">
                                Sản phẩm đồng giá
                            </span>
                        </div>
                        <div class="product-itemCard-purchase">
                            <span class="product-itemCard-purchase-price">
                                410.000đ
                            </span>
                            <a href="#" class="product-itemCard-purchase-add">
                                <svg class="product-itemCard-purchase-add-img" xmlns="http://www.w3.org/2000/svg" width="24" height="24" fill="none" viewBox="0 0 24 24">   <path fill="currentColor" fill-rule="evenodd" d="M3.24 13.196A1 1 0 0 1 4.22 12h15.56a1 1 0 0 1 .98 1.196l-1.278 6.392A3 3 0 0 1 16.541 22H7.459a3 3 0 0 1-2.941-2.412l-1.279-6.392ZM13 15a1 1 0 1 1 2 0v4a1 1 0 1 1-2 0v-4Zm-3-1a1 1 0 0 0-1 1v4a1 1 0 1 0 2 0v-4a1 1 0 0 0-1-1Z" clip-rule="evenodd"/>   <path fill="currentColor" d="M2 9a1 1 0 0 1 1-1h18a1 1 0 1 1 0 2H3a1 1 0 0 1-1-1Zm8.707-5.293a1 1 0 0 0-1.414-1.414l-2 2a1 1 0 0 0 1.414 1.414l2-2Zm2.586 0a1 1 0 0 1 1.414-1.414l2 2a1 1 0 0 1-1.414 1.414l-2-2Z"/> </svg>
                                <!-- <img src="/?" > -->
                            </a>
                        </div>
                    </div>
                </li>
                <li class="product__item">
                    <div class="product-item__card">
                        <a href="#" class="product-item-detail">
                            <img src="/?"class="product-item__img">
                        </a>
                        <div class="product-itemCard-desc">
                            <span class="product-itemCard-desc-type">New</span>
                            <span class="product-itemCard-desc-text">
                                Sản phẩm đồng giá
                            </span>
                        </div>
                        <div class="product-itemCard-purchase">
                            <span class="product-itemCard-purchase-price">
                                410.000đ
                            </span>
                            <a href="#" class="product-itemCard-purchase-add">
                                <svg class="product-itemCard-purchase-add-img" xmlns="http://www.w3.org/2000/svg" width="24" height="24" fill="none" viewBox="0 0 24 24">   <path fill="currentColor" fill-rule="evenodd" d="M3.24 13.196A1 1 0 0 1 4.22 12h15.56a1 1 0 0 1 .98 1.196l-1.278 6.392A3 3 0 0 1 16.541 22H7.459a3 3 0 0 1-2.941-2.412l-1.279-6.392ZM13 15a1 1 0 1 1 2 0v4a1 1 0 1 1-2 0v-4Zm-3-1a1 1 0 0 0-1 1v4a1 1 0 1 0 2 0v-4a1 1 0 0 0-1-1Z" clip-rule="evenodd"/>   <path fill="currentColor" d="M2 9a1 1 0 0 1 1-1h18a1 1 0 1 1 0 2H3a1 1 0 0 1-1-1Zm8.707-5.293a1 1 0 0 0-1.414-1.414l-2 2a1 1 0 0 0 1.414 1.414l2-2Zm2.586 0a1 1 0 0 1 1.414-1.414l2 2a1 1 0 0 1-1.414 1.414l-2-2Z"/> </svg>
                                <!-- <img src="/?" > -->
                            </a>
                        </div>
                    </div>
                </li>
                <li class="product__item">
                    <div class="product-item__card">
                        <a href="#" class="product-item-detail">
                            <img src="/?"class="product-item__img">
                        </a>
                        <div class="product-itemCard-desc">
                            <span class="product-itemCard-desc-type">New</span>
                            <span class="product-itemCard-desc-text">
                                Sản phẩm đồng giá
                            </span>
                        </div>
                        <div class="product-itemCard-purchase">
                            <span class="product-itemCard-purchase-price">
                                410.000đ
                            </span>
                            <a href="#" class="product-itemCard-purchase-add">
                                <svg class="product-itemCard-purchase-add-img" xmlns="http://www.w3.org/2000/svg" width="24" height="24" fill="none" viewBox="0 0 24 24">   <path fill="currentColor" fill-rule="evenodd" d="M3.24 13.196A1 1 0 0 1 4.22 12h15.56a1 1 0 0 1 .98 1.196l-1.278 6.392A3 3 0 0 1 16.541 22H7.459a3 3 0 0 1-2.941-2.412l-1.279-6.392ZM13 15a1 1 0 1 1 2 0v4a1 1 0 1 1-2 0v-4Zm-3-1a1 1 0 0 0-1 1v4a1 1 0 1 0 2 0v-4a1 1 0 0 0-1-1Z" clip-rule="evenodd"/>   <path fill="currentColor" d="M2 9a1 1 0 0 1 1-1h18a1 1 0 1 1 0 2H3a1 1 0 0 1-1-1Zm8.707-5.293a1 1 0 0 0-1.414-1.414l-2 2a1 1 0 0 0 1.414 1.414l2-2Zm2.586 0a1 1 0 0 1 1.414-1.414l2 2a1 1 0 0 1-1.414 1.414l-2-2Z"/> </svg>
                                <!-- <img src="/?" > -->
                            </a>
                        </div>
                    </div>
                </li>
                <li class="product__item">
                    <div class="product-item__card">
                        <a href="#" class="product-item-detail">
                            <img src="/?"class="product-item__img">
                        </a>
                        <div class="product-itemCard-desc">
                            <span class="product-itemCard-desc-type">New</span>
                            <span class="product-itemCard-desc-text">
                                Sản phẩm đồng giá
                            </span>
                        </div>
                        <div class="product-itemCard-purchase">
                            <span class="product-itemCard-purchase-price">
                                410.000đ
                            </span>
                            <a href="#" class="product-itemCard-purchase-add">
                                <svg class="product-itemCard-purchase-add-img" xmlns="http://www.w3.org/2000/svg" width="24" height="24" fill="none" viewBox="0 0 24 24">   <path fill="currentColor" fill-rule="evenodd" d="M3.24 13.196A1 1 0 0 1 4.22 12h15.56a1 1 0 0 1 .98 1.196l-1.278 6.392A3 3 0 0 1 16.541 22H7.459a3 3 0 0 1-2.941-2.412l-1.279-6.392ZM13 15a1 1 0 1 1 2 0v4a1 1 0 1 1-2 0v-4Zm-3-1a1 1 0 0 0-1 1v4a1 1 0 1 0 2 0v-4a1 1 0 0 0-1-1Z" clip-rule="evenodd"/>   <path fill="currentColor" d="M2 9a1 1 0 0 1 1-1h18a1 1 0 1 1 0 2H3a1 1 0 0 1-1-1Zm8.707-5.293a1 1 0 0 0-1.414-1.414l-2 2a1 1 0 0 0 1.414 1.414l2-2Zm2.586 0a1 1 0 0 1 1.414-1.414l2 2a1 1 0 0 1-1.414 1.414l-2-2Z"/> </svg>
                                <!-- <img src="/?" > -->
                            </a>
                        </div>
                    </div>
                </li>
                <li class="product__item">
                    <div class="product-item__card">
                        <a href="#" class="product-item-detail">
                            <img src="/?"class="product-item__img">
                        </a>
                        <div class="product-itemCard-desc">
                            <span class="product-itemCard-desc-type">New</span>
                            <span class="product-itemCard-desc-text">
                                Sản phẩm đồng giá
                            </span>
                        </div>
                        <div class="product-itemCard-purchase">
                            <span class="product-itemCard-purchase-price">
                                410.000đ
                            </span>
                            <a href="#" class="product-itemCard-purchase-add">
                                <svg class="product-itemCard-purchase-add-img" xmlns="http://www.w3.org/2000/svg" width="24" height="24" fill="none" viewBox="0 0 24 24">   <path fill="currentColor" fill-rule="evenodd" d="M3.24 13.196A1 1 0 0 1 4.22 12h15.56a1 1 0 0 1 .98 1.196l-1.278 6.392A3 3 0 0 1 16.541 22H7.459a3 3 0 0 1-2.941-2.412l-1.279-6.392ZM13 15a1 1 0 1 1 2 0v4a1 1 0 1 1-2 0v-4Zm-3-1a1 1 0 0 0-1 1v4a1 1 0 1 0 2 0v-4a1 1 0 0 0-1-1Z" clip-rule="evenodd"/>   <path fill="currentColor" d="M2 9a1 1 0 0 1 1-1h18a1 1 0 1 1 0 2H3a1 1 0 0 1-1-1Zm8.707-5.293a1 1 0 0 0-1.414-1.414l-2 2a1 1 0 0 0 1.414 1.414l2-2Zm2.586 0a1 1 0 0 1 1.414-1.414l2 2a1 1 0 0 1-1.414 1.414l-2-2Z"/> </svg>
                                <!-- <img src="/?" > -->
                            </a>
                        </div>
                    </div>
                </li>
                <li class="product__item">
                    <div class="product-item__card">
                        <a href="#" class="product-item-detail">
                            <img src="/?"class="product-item__img">
                        </a>
                        <div class="product-itemCard-desc">
                            <span class="product-itemCard-desc-type">New</span>
                            <span class="product-itemCard-desc-text">
                                Sản phẩm đồng giá
                            </span>
                        </div>
                        <div class="product-itemCard-purchase">
                            <span class="product-itemCard-purchase-price">
                                410.000đ
                            </span>
                            <a href="#" class="product-itemCard-purchase-add">
                                <svg class="product-itemCard-purchase-add-img" xmlns="http://www.w3.org/2000/svg" width="24" height="24" fill="none" viewBox="0 0 24 24">   <path fill="currentColor" fill-rule="evenodd" d="M3.24 13.196A1 1 0 0 1 4.22 12h15.56a1 1 0 0 1 .98 1.196l-1.278 6.392A3 3 0 0 1 16.541 22H7.459a3 3 0 0 1-2.941-2.412l-1.279-6.392ZM13 15a1 1 0 1 1 2 0v4a1 1 0 1 1-2 0v-4Zm-3-1a1 1 0 0 0-1 1v4a1 1 0 1 0 2 0v-4a1 1 0 0 0-1-1Z" clip-rule="evenodd"/>   <path fill="currentColor" d="M2 9a1 1 0 0 1 1-1h18a1 1 0 1 1 0 2H3a1 1 0 0 1-1-1Zm8.707-5.293a1 1 0 0 0-1.414-1.414l-2 2a1 1 0 0 0 1.414 1.414l2-2Zm2.586 0a1 1 0 0 1 1.414-1.414l2 2a1 1 0 0 1-1.414 1.414l-2-2Z"/> </svg>
                                <!-- <img src="/?" > -->
                            </a>
                        </div>
                    </div>
                </li>
                <li class="product__item">
                    <div class="product-item__card">
                        <a href="#" class="product-item-detail">
                            <img src="/?"class="product-item__img">
                        </a>
                        <div class="product-itemCard-desc">
                            <span class="product-itemCard-desc-type">New</span>
                            <span class="product-itemCard-desc-text">
                                Sản phẩm đồng giá
                            </span>
                        </div>
                        <div class="product-itemCard-purchase">
                            <span class="product-itemCard-purchase-price">
                                410.000đ
                            </span>
                            <a href="#" class="product-itemCard-purchase-add">
                                <svg class="product-itemCard-purchase-add-img" xmlns="http://www.w3.org/2000/svg" width="24" height="24" fill="none" viewBox="0 0 24 24">   <path fill="currentColor" fill-rule="evenodd" d="M3.24 13.196A1 1 0 0 1 4.22 12h15.56a1 1 0 0 1 .98 1.196l-1.278 6.392A3 3 0 0 1 16.541 22H7.459a3 3 0 0 1-2.941-2.412l-1.279-6.392ZM13 15a1 1 0 1 1 2 0v4a1 1 0 1 1-2 0v-4Zm-3-1a1 1 0 0 0-1 1v4a1 1 0 1 0 2 0v-4a1 1 0 0 0-1-1Z" clip-rule="evenodd"/>   <path fill="currentColor" d="M2 9a1 1 0 0 1 1-1h18a1 1 0 1 1 0 2H3a1 1 0 0 1-1-1Zm8.707-5.293a1 1 0 0 0-1.414-1.414l-2 2a1 1 0 0 0 1.414 1.414l2-2Zm2.586 0a1 1 0 0 1 1.414-1.414l2 2a1 1 0 0 1-1.414 1.414l-2-2Z"/> </svg>
                                <!-- <img src="/?" > -->
                            </a>
                        </div>
                    </div>
                </li>
                <li class="product__item">
                    <div class="product-item__card">
                        <a href="#" class="product-item-detail">
                            <img src="/?"class="product-item__img">
                        </a>
                        <div class="product-itemCard-desc">
                            <span class="product-itemCard-desc-type">New</span>
                            <span class="product-itemCard-desc-text">
                                Sản phẩm đồng giá
                            </span>
                        </div>
                        <div class="product-itemCard-purchase">
                            <span class="product-itemCard-purchase-price">
                                410.000đ
                            </span>
                            <a href="#" class="product-itemCard-purchase-add">
                                <svg class="product-itemCard-purchase-add-img" xmlns="http://www.w3.org/2000/svg" width="24" height="24" fill="none" viewBox="0 0 24 24">   <path fill="currentColor" fill-rule="evenodd" d="M3.24 13.196A1 1 0 0 1 4.22 12h15.56a1 1 0 0 1 .98 1.196l-1.278 6.392A3 3 0 0 1 16.541 22H7.459a3 3 0 0 1-2.941-2.412l-1.279-6.392ZM13 15a1 1 0 1 1 2 0v4a1 1 0 1 1-2 0v-4Zm-3-1a1 1 0 0 0-1 1v4a1 1 0 1 0 2 0v-4a1 1 0 0 0-1-1Z" clip-rule="evenodd"/>   <path fill="currentColor" d="M2 9a1 1 0 0 1 1-1h18a1 1 0 1 1 0 2H3a1 1 0 0 1-1-1Zm8.707-5.293a1 1 0 0 0-1.414-1.414l-2 2a1 1 0 0 0 1.414 1.414l2-2Zm2.586 0a1 1 0 0 1 1.414-1.414l2 2a1 1 0 0 1-1.414 1.414l-2-2Z"/> </svg>
                                <!-- <img src="/?" > -->
                            </a>
                        </div>
                    </div>
                </li>
                <li class="product__item">
                    <div class="product-item__card">
                        <a href="#" class="product-item-detail">
                            <img src="/?"class="product-item__img">
                        </a>
                        <div class="product-itemCard-desc">
                            <span class="product-itemCard-desc-type">New</span>
                            <span class="product-itemCard-desc-text">
                                Sản phẩm đồng giá
                            </span>
                        </div>
                        <div class="product-itemCard-purchase">
                            <span class="product-itemCard-purchase-price">
                                410.000đ
                            </span>
                            <a href="#" class="product-itemCard-purchase-add">
                                <svg class="product-itemCard-purchase-add-img" xmlns="http://www.w3.org/2000/svg" width="24" height="24" fill="none" viewBox="0 0 24 24">   <path fill="currentColor" fill-rule="evenodd" d="M3.24 13.196A1 1 0 0 1 4.22 12h15.56a1 1 0 0 1 .98 1.196l-1.278 6.392A3 3 0 0 1 16.541 22H7.459a3 3 0 0 1-2.941-2.412l-1.279-6.392ZM13 15a1 1 0 1 1 2 0v4a1 1 0 1 1-2 0v-4Zm-3-1a1 1 0 0 0-1 1v4a1 1 0 1 0 2 0v-4a1 1 0 0 0-1-1Z" clip-rule="evenodd"/>   <path fill="currentColor" d="M2 9a1 1 0 0 1 1-1h18a1 1 0 1 1 0 2H3a1 1 0 0 1-1-1Zm8.707-5.293a1 1 0 0 0-1.414-1.414l-2 2a1 1 0 0 0 1.414 1.414l2-2Zm2.586 0a1 1 0 0 1 1.414-1.414l2 2a1 1 0 0 1-1.414 1.414l-2-2Z"/> </svg>
                                <!-- <img src="/?" > -->
                            </a>
                        </div>
                    </div>
                </li>
                <li class="product__item">
                    <div class="product-item__card">
                        <a href="#" class="product-item-detail">
                            <img src="/?"class="product-item__img">
                        </a>
                        <div class="product-itemCard-desc">
                            <span class="product-itemCard-desc-type">New</span>
                            <span class="product-itemCard-desc-text">
                                Sản phẩm đồng giá
                            </span>
                        </div>
                        <div class="product-itemCard-purchase">
                            <span class="product-itemCard-purchase-price">
                                410.000đ
                            </span>
                            <a href="#" class="product-itemCard-purchase-add">
                                <svg class="product-itemCard-purchase-add-img" xmlns="http://www.w3.org/2000/svg" width="24" height="24" fill="none" viewBox="0 0 24 24">   <path fill="currentColor" fill-rule="evenodd" d="M3.24 13.196A1 1 0 0 1 4.22 12h15.56a1 1 0 0 1 .98 1.196l-1.278 6.392A3 3 0 0 1 16.541 22H7.459a3 3 0 0 1-2.941-2.412l-1.279-6.392ZM13 15a1 1 0 1 1 2 0v4a1 1 0 1 1-2 0v-4Zm-3-1a1 1 0 0 0-1 1v4a1 1 0 1 0 2 0v-4a1 1 0 0 0-1-1Z" clip-rule="evenodd"/>   <path fill="currentColor" d="M2 9a1 1 0 0 1 1-1h18a1 1 0 1 1 0 2H3a1 1 0 0 1-1-1Zm8.707-5.293a1 1 0 0 0-1.414-1.414l-2 2a1 1 0 0 0 1.414 1.414l2-2Zm2.586 0a1 1 0 0 1 1.414-1.414l2 2a1 1 0 0 1-1.414 1.414l-2-2Z"/> </svg>
                                <!-- <img src="/?" > -->
                            </a>
                        </div>
                    </div>
                </li>
                <li class="product__item">
                    <div class="product-item__card">
                        <a href="#" class="product-item-detail">
                            <img src="/?"class="product-item__img">
                        </a>
                        <div class="product-itemCard-desc">
                            <span class="product-itemCard-desc-type">New</span>
                            <span class="product-itemCard-desc-text">
                                Sản phẩm đồng giá
                            </span>
                        </div>
                        <div class="product-itemCard-purchase">
                            <span class="product-itemCard-purchase-price">
                                410.000đ
                            </span>
                            <a href="#" class="product-itemCard-purchase-add">
                                <svg class="product-itemCard-purchase-add-img" xmlns="http://www.w3.org/2000/svg" width="24" height="24" fill="none" viewBox="0 0 24 24">   <path fill="currentColor" fill-rule="evenodd" d="M3.24 13.196A1 1 0 0 1 4.22 12h15.56a1 1 0 0 1 .98 1.196l-1.278 6.392A3 3 0 0 1 16.541 22H7.459a3 3 0 0 1-2.941-2.412l-1.279-6.392ZM13 15a1 1 0 1 1 2 0v4a1 1 0 1 1-2 0v-4Zm-3-1a1 1 0 0 0-1 1v4a1 1 0 1 0 2 0v-4a1 1 0 0 0-1-1Z" clip-rule="evenodd"/>   <path fill="currentColor" d="M2 9a1 1 0 0 1 1-1h18a1 1 0 1 1 0 2H3a1 1 0 0 1-1-1Zm8.707-5.293a1 1 0 0 0-1.414-1.414l-2 2a1 1 0 0 0 1.414 1.414l2-2Zm2.586 0a1 1 0 0 1 1.414-1.414l2 2a1 1 0 0 1-1.414 1.414l-2-2Z"/> </svg>
                                <!-- <img src="/?" > -->
                            </a>
                        </div>
                    </div>
                </li>
                <li class="product__item">
                    <div class="product-item__card">
                        <a href="#" class="product-item-detail">
                            <img src="/?"class="product-item__img">
                        </a>
                        <div class="product-itemCard-desc">
                            <span class="product-itemCard-desc-type">New</span>
                            <span class="product-itemCard-desc-text">
                                Sản phẩm đồng giá
                            </span>
                        </div>
                        <div class="product-itemCard-purchase">
                            <span class="product-itemCard-purchase-price">
                                410.000đ
                            </span>
                            <a href="#" class="product-itemCard-purchase-add">
                                <svg class="product-itemCard-purchase-add-img" xmlns="http://www.w3.org/2000/svg" width="24" height="24" fill="none" viewBox="0 0 24 24">   <path fill="currentColor" fill-rule="evenodd" d="M3.24 13.196A1 1 0 0 1 4.22 12h15.56a1 1 0 0 1 .98 1.196l-1.278 6.392A3 3 0 0 1 16.541 22H7.459a3 3 0 0 1-2.941-2.412l-1.279-6.392ZM13 15a1 1 0 1 1 2 0v4a1 1 0 1 1-2 0v-4Zm-3-1a1 1 0 0 0-1 1v4a1 1 0 1 0 2 0v-4a1 1 0 0 0-1-1Z" clip-rule="evenodd"/>   <path fill="currentColor" d="M2 9a1 1 0 0 1 1-1h18a1 1 0 1 1 0 2H3a1 1 0 0 1-1-1Zm8.707-5.293a1 1 0 0 0-1.414-1.414l-2 2a1 1 0 0 0 1.414 1.414l2-2Zm2.586 0a1 1 0 0 1 1.414-1.414l2 2a1 1 0 0 1-1.414 1.414l-2-2Z"/> </svg>
                                <!-- <img src="/?" > -->
                            </a>
                        </div>
                    </div>
                </li>
                <li class="product__item">
                    <div class="product-item__card">
                        <a href="#" class="product-item-detail">
                            <img src="/?"class="product-item__img">
                        </a>
                        <div class="product-itemCard-desc">
                            <span class="product-itemCard-desc-type">New</span>
                            <span class="product-itemCard-desc-text">
                                Sản phẩm đồng giá
                            </span>
                        </div>
                        <div class="product-itemCard-purchase">
                            <span class="product-itemCard-purchase-price">
                                410.000đ
                            </span>
                            <a href="#" class="product-itemCard-purchase-add">
                                <svg class="product-itemCard-purchase-add-img" xmlns="http://www.w3.org/2000/svg" width="24" height="24" fill="none" viewBox="0 0 24 24">   <path fill="currentColor" fill-rule="evenodd" d="M3.24 13.196A1 1 0 0 1 4.22 12h15.56a1 1 0 0 1 .98 1.196l-1.278 6.392A3 3 0 0 1 16.541 22H7.459a3 3 0 0 1-2.941-2.412l-1.279-6.392ZM13 15a1 1 0 1 1 2 0v4a1 1 0 1 1-2 0v-4Zm-3-1a1 1 0 0 0-1 1v4a1 1 0 1 0 2 0v-4a1 1 0 0 0-1-1Z" clip-rule="evenodd"/>   <path fill="currentColor" d="M2 9a1 1 0 0 1 1-1h18a1 1 0 1 1 0 2H3a1 1 0 0 1-1-1Zm8.707-5.293a1 1 0 0 0-1.414-1.414l-2 2a1 1 0 0 0 1.414 1.414l2-2Zm2.586 0a1 1 0 0 1 1.414-1.414l2 2a1 1 0 0 1-1.414 1.414l-2-2Z"/> </svg>
                                <!-- <img src="/?" > -->
                            </a>
                        </div>
                    </div>
                </li>
                <li class="product__item">
                    <div class="product-item__card">
                        <a href="#" class="product-item-detail">
                            <img src="/?"class="product-item__img">
                        </a>
                        <div class="product-itemCard-desc">
                            <span class="product-itemCard-desc-type">New</span>
                            <span class="product-itemCard-desc-text">
                                Sản phẩm đồng giá
                            </span>
                        </div>
                        <div class="product-itemCard-purchase">
                            <span class="product-itemCard-purchase-price">
                                410.000đ
                            </span>
                            <a href="#" class="product-itemCard-purchase-add">
                                <svg class="product-itemCard-purchase-add-img" xmlns="http://www.w3.org/2000/svg" width="24" height="24" fill="none" viewBox="0 0 24 24">   <path fill="currentColor" fill-rule="evenodd" d="M3.24 13.196A1 1 0 0 1 4.22 12h15.56a1 1 0 0 1 .98 1.196l-1.278 6.392A3 3 0 0 1 16.541 22H7.459a3 3 0 0 1-2.941-2.412l-1.279-6.392ZM13 15a1 1 0 1 1 2 0v4a1 1 0 1 1-2 0v-4Zm-3-1a1 1 0 0 0-1 1v4a1 1 0 1 0 2 0v-4a1 1 0 0 0-1-1Z" clip-rule="evenodd"/>   <path fill="currentColor" d="M2 9a1 1 0 0 1 1-1h18a1 1 0 1 1 0 2H3a1 1 0 0 1-1-1Zm8.707-5.293a1 1 0 0 0-1.414-1.414l-2 2a1 1 0 0 0 1.414 1.414l2-2Zm2.586 0a1 1 0 0 1 1.414-1.414l2 2a1 1 0 0 1-1.414 1.414l-2-2Z"/> </svg>
                                <!-- <img src="/?" > -->
                            </a>
                        </div>
                    </div>
                </li>
                <li class="product__item">
                    <div class="product-item__card">
                        <a href="#" class="product-item-detail">
                            <img src="/?"class="product-item__img">
                        </a>
                        <div class="product-itemCard-desc">
                            <span class="product-itemCard-desc-type">New</span>
                            <span class="product-itemCard-desc-text">
                                Sản phẩm đồng giá
                            </span>
                        </div>
                        <div class="product-itemCard-purchase">
                            <span class="product-itemCard-purchase-price">
                                410.000đ
                            </span>
                            <a href="#" class="product-itemCard-purchase-add">
                                <svg class="product-itemCard-purchase-add-img" xmlns="http://www.w3.org/2000/svg" width="24" height="24" fill="none" viewBox="0 0 24 24">   <path fill="currentColor" fill-rule="evenodd" d="M3.24 13.196A1 1 0 0 1 4.22 12h15.56a1 1 0 0 1 .98 1.196l-1.278 6.392A3 3 0 0 1 16.541 22H7.459a3 3 0 0 1-2.941-2.412l-1.279-6.392ZM13 15a1 1 0 1 1 2 0v4a1 1 0 1 1-2 0v-4Zm-3-1a1 1 0 0 0-1 1v4a1 1 0 1 0 2 0v-4a1 1 0 0 0-1-1Z" clip-rule="evenodd"/>   <path fill="currentColor" d="M2 9a1 1 0 0 1 1-1h18a1 1 0 1 1 0 2H3a1 1 0 0 1-1-1Zm8.707-5.293a1 1 0 0 0-1.414-1.414l-2 2a1 1 0 0 0 1.414 1.414l2-2Zm2.586 0a1 1 0 0 1 1.414-1.414l2 2a1 1 0 0 1-1.414 1.414l-2-2Z"/> </svg>
                                <!-- <img src="/?" > -->
                            </a>
                        </div>
                    </div>
                </li>
                <li class="product__item">
                    <div class="product-item__card">
                        <a href="#" class="product-item-detail">
                            <img src="/?"class="product-item__img">
                        </a>
                        <div class="product-itemCard-desc">
                            <span class="product-itemCard-desc-type">New</span>
                            <span class="product-itemCard-desc-text">
                                Sản phẩm đồng giá
                            </span>
                        </div>
                        <div class="product-itemCard-purchase">
                            <span class="product-itemCard-purchase-price">
                                410.000đ
                            </span>
                            <a href="#" class="product-itemCard-purchase-add">
                                <svg class="product-itemCard-purchase-add-img" xmlns="http://www.w3.org/2000/svg" width="24" height="24" fill="none" viewBox="0 0 24 24">   <path fill="currentColor" fill-rule="evenodd" d="M3.24 13.196A1 1 0 0 1 4.22 12h15.56a1 1 0 0 1 .98 1.196l-1.278 6.392A3 3 0 0 1 16.541 22H7.459a3 3 0 0 1-2.941-2.412l-1.279-6.392ZM13 15a1 1 0 1 1 2 0v4a1 1 0 1 1-2 0v-4Zm-3-1a1 1 0 0 0-1 1v4a1 1 0 1 0 2 0v-4a1 1 0 0 0-1-1Z" clip-rule="evenodd"/>   <path fill="currentColor" d="M2 9a1 1 0 0 1 1-1h18a1 1 0 1 1 0 2H3a1 1 0 0 1-1-1Zm8.707-5.293a1 1 0 0 0-1.414-1.414l-2 2a1 1 0 0 0 1.414 1.414l2-2Zm2.586 0a1 1 0 0 1 1.414-1.414l2 2a1 1 0 0 1-1.414 1.414l-2-2Z"/> </svg>
                                <!-- <img src="/?" > -->
                            </a>
                        </div>
                    </div>
                </li>
            </ul>
        </div>
    </div>
