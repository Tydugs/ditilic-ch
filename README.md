<!DOCTYPE html>
<html lang="vi">
<head>
<script src="https://kit.fontawesome.com/938b0cef03.js" crossorigin="anonymous"></script>    <meta charset="UTF-8">
<script src="https://code.jquery.com/jquery-3.7.1.js"></script> 
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Đình - Đền - Chùa Cầu Muối</title>
    <style>
        * { box-sizing: border-box; margin: 0; padding: 0; }
        body { font-family: Arial, sans-serif; background-color: #f4f1e7; color: #973e0a; }
        header { background: #a72b0c; color: white; padding: 30px; text-align: center; font-size: 54px; }
        .slider-container { position: relative; max-width: 100%; overflow: hidden; margin-top: 20px; }
        .slides { display: flex; transition: transform 0.5s ease-in-out; }
        .slide { min-width: 50%; }
        img { width: 60%; height: auto; }
        .prev, .next {
            position: absolute; top: 50%; transform: translateY(-50%);
            background: rgba(0, 0, 0, 0.5); color: white;
            border: none; padding: 10px; cursor: pointer;
        }
        .prev { left: 10px; }
        .next { right: 10px; }
        .content { padding: 10px; max-width: 900px; margin: auto; }
        footer { background:#f4a361; color: white; text-align: center; padding: 10px; margin-top: 20px; }
        .slider-container {
    position: relative;
    max-width: 100%;
    overflow: hidden;
    margin-top: 20px;
}

.slides {
    display: flex;
    transition: transform 0.5s ease-in-out;
    gap: 10px; 
    justify-content: center;
}

.slide {
    flex: 0 0 20%;
    text-align: center;
}

.slide img {
    width: 100%; 
    height: 300px;
    object-fit: cover; 
    border-radius: 10px; 
}


    </style>
</head>
<body>
    <header>Đình - Đền - Chùa Cầu Muối</header>
    <div class="slider-container">
        <div class="slides">
            <div class="slide"><img src="https://scontent.fhph1-1.fna.fbcdn.net/v/t39.30808-6/476229133_608871261884251_895161057902814393_n.jpg?_nc_cat=110&ccb=1-7&_nc_sid=f727a1&_nc_eui2=AeHg4mURw29CYQqrmZSMjdPlmoiXkeAUo-6aiJeR4BSj7rFh2Cua-y6hk-RvVnyKQJhci9ik1zpAn09WuG_EeisT&_nc_ohc=-8jEgTI4yGcQ7kNvgHbXyvW&_nc_oc=Adjktl8S7JZjW0SxE6p_5DuCcnV9_ty4hhsSJuTNvX11Hrje5CnBnp7leUi4KlY13VSrO1BXfa7YJjUbANAf80Ek&_nc_zt=23&_nc_ht=scontent.fhph1-1.fna&_nc_gid=AP1OxleO4YaCJixRnuCU703&oh=00_AYBPcjXznxYLmlAWNcWt0kurqj83uLpY53-VmYZ3ENV3vQ&oe=67BA7BF3" alt="CầuMuối"></div>
            <div class="slide"><img src="https://scontent.fhph2-1.fna.fbcdn.net/v/t39.30808-6/476112848_608870445217666_5908913683567099598_n.jpg?_nc_cat=111&ccb=1-7&_nc_sid=f727a1&_nc_eui2=AeHdiqqfPIp1u_iraZG2OwifxKtt4uCX3fXEq23i4Jfd9QmgOKuV-HBeTwW6bnBCIylrWocONwk7XszIyWFbjpsS&_nc_ohc=pWzQwbLnatIQ7kNvgFVINWE&_nc_oc=AdiAUIegOTW1LbtcSK6ma3drgfaz1BWC4ZdNt6FtjWlygYctXq9E2PdBEngE0__AQCQHyHr50C9PA6Vw-4d6nsUX&_nc_zt=23&_nc_ht=scontent.fhph2-1.fna&_nc_gid=AePxl6cE1KC95k5zA2D8mRw&oh=00_AYAwN9wkjQB8HTIfwx5xKNzM8iN_g2ZsUmeudoFRoh-pBw&oe=67BA7D56" alt="Cầu muối"></div>
            <div class="slide"><img src="https://scontent.fhph1-1.fna.fbcdn.net/v/t39.30808-6/476354586_608871925217518_6601598108722089943_n.jpg?_nc_cat=104&ccb=1-7&_nc_sid=f727a1&_nc_eui2=AeE46D0YgpdCzx2nt4stLcuqgY06j5It3VuBjTqPki3dW23Uegc3qOJxgqVgUO7Uj05LEWukQJgyDBMiaV001jAX&_nc_ohc=ggOTlpFoMR0Q7kNvgFQUIz9&_nc_oc=Adjrrrb5yfsPtWO-7P_VV1Am0xlayvaVFh8j3sQYTV7nI9ivsbJWC-R8ukb-SHhH_pJ6NshWpqItqAEFBrMyPuDP&_nc_zt=23&_nc_ht=scontent.fhph1-1.fna&_nc_gid=AOmE6KVgEAThSzP3hAhJdjg&oh=00_AYB6Fqwza3FI34DKVLmbTO5ifdTcZC9sXJ2y2khuFUkYNQ&oe=67BA6687" alt="Cầumuối"></div>
            <div class="slide"><img src="https://baothainguyen.vn/file/e7837c027f6ecd14017ffa4e5f2a0e34/022025/danh-trong_20250201142218.jpg" alt="Đền Công Đồng"></div>
            <div class="slide"><img src="https://khamphadisan.com.vn/wp-content/uploads/2018/09/den-muoi-thai-nguyen-khamphadisan-4.jpg" alt="cầu muối"></div>
            <div class="slide"><img src="https://scontent.fhph2-1.fna.fbcdn.net/v/t1.15752-9/479499342_637194345516502_4806216897796631183_n.jpg?stp=dst-jpg_s480x480_tt6&_nc_cat=109&ccb=1-7&_nc_sid=0024fc&_nc_eui2=AeFPU0xtshlrrA8txmu9RF9oUgey5QUfoYxSB7LlBR-hjHAhl7AbCY35FQRR9aF75dl6wd24XhT6QbtIRDNwdmrQ&_nc_ohc=xR0dhzLe1qMQ7kNvgGVHdVw&_nc_oc=AdgDbpDE8fPCfmX0fURMnlCNXXOBbFzZE5lGQ4vaz4flfIGB1ynTyoHvKe3Zpx9wzTVqNXbEUmP4WvS_kcmXUDwg&_nc_ad=z-m&_nc_cid=0&_nc_zt=23&_nc_ht=scontent.fhph2-1.fna&oh=03_Q7cD1gFHayxsVqCaOhBuv-ZMMUy2y8o6rUd308SQc_zRTqaOsA&oe=67DC2536" alt="Đình Cầu Muối"></div>
            <div class="slide"><img src="https://baothainguyen.vn/file/e7837c027f6ecd14017ffa4e5f2a0e34/012025/trang-tri-dinh-cau-muoi_20250121102740.jpg" alt="Đình Cầu Muối"></div>
            <div class="slide"><img src="https://scontent.fhph1-1.fna.fbcdn.net/v/t39.30808-6/476159474_608870791884298_2587482826714599165_n.jpg?_nc_cat=110&ccb=1-7&_nc_sid=f727a1&_nc_eui2=AeEG_xFJI1iqbSm6kqrXlDwjddQpSYmjhhp11ClJiaOGGoB2tEFtQh3BVvS8IFVgk3aIt_E651XQJ1NE6LGMPAhX&_nc_ohc=x9xoLCZQLg4Q7kNvgHdkQ5Y&_nc_oc=Adh06i7Zs2OvmpSl5T11fD8JuxJtZU5wN00QCtZgLHLc2haH-6jf1cPeU3loa-lG7slzwgZrppWxs8RBs7Zby4WK&_nc_zt=23&_nc_ht=scontent.fhph1-1.fna&_nc_gid=A00h0p6NGBlymEkyZLkMCOR&oh=00_AYDcIq3P1rjFqtR5LFZUN1E-vrn86Eej6yWuswp8nLsB6g&oe=67B81F40" alt="Đình cầu Muối"></div>
            <div class="slide"><img src="https://khamphadisan.com.vn/wp-content/uploads/2018/09/den-muoi-thai-nguyen-khamphadisan-5.jpg" alt="cầu Muối"></div>
            <div class="slide"><img src="https://scontent.fhph1-2.fna.fbcdn.net/v/t39.30808-6/476019034_608870698550974_6000100008888896391_n.jpg?_nc_cat=108&ccb=1-7&_nc_sid=f727a1&_nc_eui2=AeEPYcXn3lLq-flxqGa84mXgUMRZ5ObNIYVQxFnk5s0hhQ-yN50tKlApbumX1VWq6hEZFrMfw-1JmT0uK0kjXCnA&_nc_ohc=YIlQHevC140Q7kNvgE-gEv8&_nc_oc=AdhcqfOT282evXoUxnR1gOJD_I2fYgUbEO1wfE3BIIkN5Ys4QJCme5lkF7u463O2r0S8ALDTarLh07qodxQYUxGH&_nc_zt=23&_nc_ht=scontent.fhph1-2.fna&_nc_gid=AVQl_OBxmkAara2-io9z453&oh=00_AYDA21siM0vDCpcTfrRCVjwyE3vsB_3qNQrUvGptarLtcA&oe=67B805BF" alt="Cầu MuốI"></div>
            <div class="slide"><img src="https://scontent.fhph1-3.fna.fbcdn.net/v/t39.30808-6/476329062_608871301884247_2584281519768149589_n.jpg?_nc_cat=103&ccb=1-7&_nc_sid=f727a1&_nc_eui2=AeFv3GmHDsqL6pJTpY2uAX7ARJLqLPugbUVEkuos-6BtRXEgdKkFXAWosWpKOHE_ey40a2aoujB3yuKHaKrG3T8x&_nc_ohc=qjkLCC0qQyEQ7kNvgEHCnWk&_nc_oc=AdhI74Wg1qBvDJ8CvB8BmqV3QE0xtl_tI9OUIabRLIXSyJX3iofobfH584k3c4eUF6BH87GrjvF85SIgkHY7P-ZX&_nc_zt=23&_nc_ht=scontent.fhph1-3.fna&_nc_gid=A6ixPQ3u6DhYnghh2oWe3MC&oh=00_AYAontjVU6zINIILiNc7SGbkcwnm3uPnIrBsfz0mVsPgZQ&oe=67B8033A" alt="cầumuối"></div>

        </div>
        <button class="prev" onclick="moveSlide(-1)">&#10094;</button>
        <button class="next" onclick="moveSlide(1)">&#10095;</button>
    </div>
        
    <body>
        <div class="content">
        <style>
            * {
                margin: 0;
                padding: 0;
            }       
            #wrapper {
                max-width: 600px;
                margin: 0px auto;
                text-align: justify;
            }
            h1 {
                text-align: center;
                margin-bottom: 30px;
            }
            .accordion-header {
                display: flex;
                justify-content: space-between;
                align-items: center;
                background: #fad4ba; 
                padding: 10px 10px;
                margin-bottom: 10px;
                cursor: pointer;
            }  
            .accordion-item.active .accordion-header {
                background: #f5e982;
                coler: #d85959;
            }
            .arrow {
                transition: all 0.4s;
            }
            .accordion-item.active .arrow {
                transform: rotate(180deg);
            }
            .accordion-body {
               padding: 10px 10px;
               display: none;
            }  
        </style>
        <script>
            $(document).ready(function() {
                $('.accordion-item.active .accordion-body').slideDown();
                $('.accordion-header').click(function() {
                    $(this).parent().toggleClass('active');
                    $(this).parent().children('.accordion-body').slideToggle();
                });    
            });
        </script>
        <div id="wrapper">
             <h1>Tổng quan về khu di tích lịch sử đình - đền - chùa Cầu Muối</h1>
             <div class="accordion">
                  <div class="accordion-item active">
                       <div class="accordion-header">                        
                        <h3>Giới thiệu</h3>
                        <i class="arrow fa-solid fa-angle-down"></i>
                       </div>
                       <div class="accordion-body">
                         <p>Huyện Phú Bình không chỉ nổi tiếng là vựa lúa của tỉnh Thái Nguyên mà còn được biết đến với nhiều lễ hội truyền thống, di tích lịch sử - văn hóa lâu đời, trong đó nổi bật là Cụm di tích Đình - đền - chùa Cầu Muối. Trải qua hàng trăm năm, Cụm di tích vẫn giữ nguyên những giá trị lịch sử, văn hóa, là nơi kết tinh nét đẹp văn hóa tín ngưỡng của cộng đồng dân cư.Cụm di tích Đình - đền - chùa Cầu Muối tọa lạc tại trung tâm xóm Cầu Muối, xã Tân Thành (Phú Bình). Nằm ở khu vực trung tâm của Cụm di tích là đình Cầu Muối. Đình là nơi thờ Thành Hoàng Cao Sơn Quý Minh Đại Vương (tức Dương Tự Minh), một danh tướng thời nhà Lý. Ông đã có những đóng góp to lớn trong việc đánh đuổi giặc ngoại xâm, bảo vệ vững chắc vùng biên cương phía Bắc của Đại Việt và phát triển kinh tế phủ Phú Lương xưa. Ghi nhớ công lao của ông, nhân dân đã lập đình để thờ cúng và tôn ông là Thành Hoàng làng.

Trong quần thể của Cụm di tích còn có chùa Cầu Muối thờ Phật; đền Công Đồng thờ Mẫu Liễu Hạnh và đền Thượng thờ Mẫu Thượng Ngàn. Trong đó, đền Công Đồng tương truyền là nơi rất linh ứng và thiêng liêng. Tục truyền rằng, Thánh Mẫu Liễu Hạnh nổi tiếng về sự hiếu đạo, được người đời truyền tụng, suy tôn là mẹ của muôn người. Bà là biểu tượng cho sức mạnh của phụ nữ, đề cao giá trị hạnh phúc, tự do và độc lập.

Không chỉ có giá trị về văn hóa, tín ngưỡng, Cụm di tích Đình - đền - chùa Cầu Muối còn là một di tích cách mạng quan trọng, đã ghi dấu nhiều sự kiện lịch sử trong hai cuộc kháng chiến chống Pháp và chống Mỹ. Năm 1948, đình, chùa Cầu Muối là nơi dạy chữ quốc ngữ, xóa nạn mù chữ cho nhân dân địa phương.

Ngoài ra, Cụm di tích còn là nơi cất giấu lương thực của huyện Phú Bình vào năm 1951; nơi đóng quân của Đại đoàn 308 trong kháng chiến chống thực dân Pháp và Sư đoàn 304 trong kháng chiến chống đế quốc Mỹ.</p>
                       </div>
                  </div>
                  <div class="accordion-item active">
                       <div class="accordion-header">
                            <h3>Lịch sử hình Thành</h3>
                            <i class="arrow fa-solid fa-angle-down"></i>
                       </div>
                       <div class="accordion-body">
                          <p>Cụm di tích đình – đền – chùa Cầu Muối xây dựng từ thời Hậu Lê, cách đây khoảng 300 năm, được đặt tên theo địa danh của làng. Cụm di tích gồm 1 đình, 2 đền và 1 chùa, nằm ở thế tựa lưng vào núi,  bao quanh là rừng xanh tươi tốt, tạo nên nét cổ kính, linh thiêng.

Trải qua thời gian, đặc biệt là 2 cuộc kháng chiến chống thực dân Pháp và Mỹ, đình - đền - chùa Cầu Muối đã được tôn tạo và tu sửa nhiều lần, trở thành nơi sinh hoạt văn hóa, tín ngưỡng tâm linh của người dân địa phương và khách thập phương.Trước đây, Cụm di tích này chỉ mở cửa đón nhân dân địa phương đến làm lễ vào ngày Sóc, ngày Vọng, tức ngày mùng một, ngày rằm theo lịch trăng hàng tháng.</p>
                       </div>
                  </div>
                  <div class="accordion-item active">
                       <div class="accordion-header">
                            <h3>Kiến Trúc</h3>
                            <i class="arrow fa-solid fa-angle-down"></i>
                       </div>
                       <div class="accordion-body">
                          <p>Các công trình trong cụm di tích đều mang phong cách kiến trúc cổ truyền. Đến nay, Cụm di tích này còn lưu giữ được nhiều hiện vật gốc có giá trị nghệ thuật và niên đại cổ xưa như: Chiêng núm đồng; chuông nhí đồng,  giá văn tế, nhang án, ngai thờ, cối đá, 5 bát hương gốm cổ, 23 pho tượng và cây hương đá được lập năm 1719...</p>
                       </div>
                  </div>
                  <div class="accordion-item active">
                       <div class="accordion-header">
                            <h3>Lễ hội</h3>
                            <i class="arrow fa-solid fa-angle-down"></i>
                       </div>
                       <div class="accordion-body">
                          <p>Lễ hội Đình - đền - chùa Cầu Muối được tổ chức hằng năm vào dịp đầu Xuân để tưởng nhớ công lao của các anh hùng đã có công đáng đuổi giặc ngoại xâm, bảo vệ Tổ quốc; đồng thời cầu cho mưa thuận gió hòa, mùa màng tốt tươi. Đây là một trong những lễ hội thu hút đông đảo du khách thập phương. “Đầu năm mua muối, cuối năm mua vôi” là tập tục từ xa xưa của người Việt. Tín ngưỡng dân gian này đã được bảo tồn, gìn giữ hàng trăm năm nay tại đình - đền - chùa Cầu Muối vào mỗi dịp đầu Xuân, năm mới. Khi đến nơi đây, mỗi người dân đều đặt gói muối, gói gạo lên mâm lễ để dâng các vị thần linh nhằm cầu mong năm mới gặp nhiều may mắn, sức khỏe, cuộc sống ấm no, bình an, hạnh phúc.Vào ngày mùng 4 tháng Giêng hàng năm, UBND huyện tổ chức Lễ hội để tuyên truyền, quảng bá các giá trị văn hóa, lịch sử của cụm di tích. Trong ngày này, Ban Quản lý sẽ thực hiện nghi lễ rước kiệu, dâng hương, thỉnh chuông cầu an, cầu lộc. Trong mâm lễ, ngoài lễ chay và lễ mặn thì không thể thiếu muối và gạo. Đây chính là nét đẹp văn hóa, nét đặc trưng của lễ hội đình - đền - chùa Cầu Muối từ xưa đến nay.

Cùng với bảo tồn những giá trị văn hóa tín ngưỡng, thời gian qua, các cấp chính quyền luôn đẩy mạnh tuyên truyền, nâng cao nhận thức của cộng đồng, nhất là thanh, thiếu niên, nhi đồng về bảo tồn, phát huy giá trị Di tích lịch sử văn hóa Đình - đền - chùa Cầu Muối.</p>
                       </div>
                  </div>
             </div>
        </div>
        
    </div>
    </body>
    <footer>&copy; 2025 Đình - Đền - Chùa Cầu Muối. Mọi quyền được bảo lưu.</footer>
    <script>
        let index = 0;
        function moveSlide(step) {
            const slides = document.querySelector('.slides');
            const totalSlides = document.querySelectorAll('.slide').length;
            index = (index + step + totalSlides) % totalSlides;
            slides.style.transform = `translateX(-${index * 100}%)`;
        }
    </script>
</body>
</html>
