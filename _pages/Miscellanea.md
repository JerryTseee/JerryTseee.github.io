---
permalink: /Miscellanea/
title: "Miscellanea"
excerpt: ""
author_profile: true
---

# My Hobbies 🐱
I like travelling, and record the world (Hover over city markers on the map to see photos!)

<div class="travel-section">
    <div id="map"></div>
</div>
<!-- Leaflet CSS -->
<link rel="stylesheet" href="https://unpkg.com/leaflet@1.9.4/dist/leaflet.css" />
<style>
    #map {
        height: 300px;
        width: 100%;
    }
    .custom-tooltip {
        max-width: 400px;
    }
    .custom-tooltip img {
        max-width: 100%;
        height: auto;
        margin-top: 5px;
    }
</style>

<!-- Leaflet JS -->
<script src="https://unpkg.com/leaflet@1.9.4/dist/leaflet.js"></script>
<script>
    // Initialize the map centered on Asia
    var map = L.map('map').setView([35.0, 105.0], 4); // Centered on Asia, zoom level 4

    // Add OpenStreetMap tiles
    L.tileLayer('https://{s}.tile.openstreetmap.org/{z}/{x}/{y}.png', {
        attribution: '&copy; <a href="https://www.openstreetmap.org/copyright">OpenStreetMap</a> contributors'
    }).addTo(map);

    // Define cities with coordinates and photo URLs
    var cities = [
        { name: 'Kuala Lumpur, Malaysia', coords: [3.1390, 101.6869], photo: '/images/kkl.jpg' },
        { name: 'Hong Kong', coords: [22.3193, 114.1694], photo: '/images/p2.jpg' },
        { name: 'Yunnan, China', coords: [24.9740, 101.4870], photo: '/images/p3.jpg' },
        { name: 'Yunnan, China', coords: [24.9740, 101.4870], photo: '/images/p4.jpg' },
        { name: 'Yunnan, China', coords: [24.9740, 101.4870], photo: '/images/p5.jpg' },
        { name: 'Guangzhou, China', coords: [23.1291, 113.2644], photo: '/images/p8.jpg' },
        { name: 'Taipei, Taiwan', coords: [25.0320, 121.5654], photo: '/images/p10.jpg' },
        { name: 'Taipei, Taiwan', coords: [25.0320, 121.5654], photo: '/images/p11.jpg' },
        { name: 'Fujian, China', coords: [26.0800, 119.2960], photo: '/images/p12.jpg' },
        { name: 'Kaohsiung, Taiwan', coords: [22.6273, 120.3014], photo: '/images/p13.jpg' },
        { name: 'Chongqing, China', coords: [29.5628, 106.5528], photo: '/images/p14.jpg' },
        { name: 'Nanjing, China', coords: [32.0603, 118.7969], photo: '/images/p15.jpg' },
        { name: 'Shanghai, China', coords: [31.2304, 121.4737], photo: '/images/sh.jpg' },
        { name: 'Maldives', coords: [3.2028, 73.2207], photo: '/images/maldives.jpg' },
        { name: 'Guilin, China', coords: [25.2743, 110.1081], photo: '/images/guilin.jpg' },
        { name: 'Beijing, China', coords: [39.9042, 116.4074], photo: '/images/BJ.jpg' },
        { name: 'Malacca, Malaysia', coords: [2.1896, 102.2501], photo: '/images/lj.jpg' },
        { name: 'Guizhou, China', coords: [26.8154, 106.8748], photo: '/images/bz.jpg' }
    ];

    // Add markers for each city
    cities.forEach(function(city) {
        var marker = L.marker(city.coords).addTo(map);
        
        // Custom tooltip on hover with larger photo
        marker.bindTooltip(
            '<div class="custom-tooltip">' +
            '<strong>' + city.name + '</strong><br>' +
            '<img src="' + city.photo + '" alt="' + city.name + ' Photo">' +
            '</div>',
            { 
                permanent: false, 
                direction: 'auto',
                className: 'custom-tooltip'
            }
        );
    });
</script>

And I like drawing

<div style="display: flex; flex-wrap: wrap; gap: 10px;">
  <img src="/images/r.jpg" alt="wolf 1" style="width: 90px; height: auto;">
  <img src="/images/m.jpg" alt="wolf 1" style="width: 90px; height: auto;">
  <img src="/images/wolf1.jpg" alt="wolf 1" style="width: 90px; height: auto;">
  <img src="/images/wolf2.jpg" alt="wolf 2" style="width: 90px; height: auto;">
  <img src="/images/T.jpg" alt="T" style="width: 90px; height: auto;">
  <img src="/images/batman.jpg" alt="batman" style="width: 90px; height: auto;">
  <img src="/images/girl.jpg" alt="girl" style="width: 90px; height: auto;">
  <img src="/images/god.jpg" alt="god" style="width: 90px; height: auto;">
  <img src="/images/scary.jpg" alt="scary" style="width: 90px; height: auto;">
  <img src="/images/moonnight.jpg" alt="moonnight" style="width: 90px; height: auto;">
</div>


# Volunteer Experience ✨
- 2025 SJTU "Save the Traditional Villages in China" Workshop
- 2025 Robocon Hong Kong Student Volunteer
- Hong Kong Hakka Associations Student Volunteer
- 2023 BTP Yunnan Program Summer Volunteer Teacher


# Media 🎉
<div style="max-width: 800px; margin: 1rem 0; padding: 1rem; border: 1px solid #ccc; background-color: #f9f9f9; height: 100px; overflow-y: scroll; text-align: left;">
  <p>
    <a href="https://mp.weixin.qq.com/s/Vo-YghwGJwpu2vSzy-obGg" target="_blank">
      《2025 年度客家子弟獎助學金頒獎典禮圓滿舉行》
    </a>
  </p>
  <p>
    <a href="https://mp.weixin.qq.com/s/V8Fb1FWmlL-dcM2A_ly4tw" target="_blank">
      《上海交通大学建筑遗产保护中心, 2025 “拯救传统村落”工作营成果展示》
    </a>
  </p>
  <p>
    <a href="https://www.hkstp.org/en/park-life/news-and-events/news/robocon-2025">
      《2025 Robocon Hong Kong Contest 机器人大赛香港赛区》
    </a>
  </p>
  <p>
    <a href="https://hkhakka.com/activities/2023-2024%e5%b9%b4%e5%ba%a6%e5%ae%a2%e5%ae%b6%e5%ad%90%e5%bc%9f%e7%8d%8e%e5%8a%a9%e5%ad%b8%e9%87%91%e9%a0%92%e7%8d%8e%e5%85%b8%e7%a6%ae%e5%9c%93%e6%bb%bf%e8%88%89%e8%a1%8c/">
      《2024 年度客家子弟獎助學金頒獎典禮圓滿舉行》
    </a>
  </p>
  <p>
    <a href="https://hkhakka.com/activities/%e9%a6%99%e6%b8%af%e5%ae%a2%e5%b1%ac%e7%b8%bd%e6%9c%83%e9%9d%92%e5%b9%b4%e9%83%a8%e8%88%89%e8%be%a6%e7%a6%8f%e5%bb%ba%e5%ad%b8%e7%bf%92%e4%ba%a4%e6%b5%81%e5%9c%98/">
      《2023 香港客屬總會青年部舉辦福建學習交流團》
    </a>
  </p>
  <p>
    <a href="https://hkhakka.com/activities/2022-2023%e5%b9%b4%e5%ba%a6%e5%ae%a2%e5%ae%b6%e5%ad%90%e5%bc%9f%e7%8d%8e%e5%8a%a9%e5%ad%b8%e9%87%91%e9%a0%92%e7%8d%8e%e5%85%b8%e7%a6%ae%e5%9c%93%e6%bb%bf%e8%88%89%e8%a1%8c/">
      《2023 年度客家子弟獎助學金頒獎典禮圓滿舉行》
    </a>
  </p>
  <p>
    <a href="https://mp.weixin.qq.com/s/PzIgrw0GnTRxF-ZbWTHHOg">
      《2023 香港大学BTP云之彼端项目组云南支教报告》
    </a>
  </p>
</div>

# Fun Facts About Me 😎
- I am interested in fencing (HKU Epee fencing team), photography, drawing, basketball and guitar
- I can speak English, Cantonese, Mandarin, Southwestern Mandarin, and a little bit of Japanese
- I am "half HongKonger, half Sichuanese", and I used to live in Zhuhai (a beautiful small city) for more than 10 years

<div style="display: flex; flex-wrap: wrap; gap: 10px;">
  <img src="/images/guitar.jpg" alt="wolf 1" style="width: 100px; height: auto;">
  <img src="/images/photography.jpg" alt="wolf 1" style="width: 100px; height: auto;">
  <img src="/images/fencing.jpg" alt="wolf 1" style="width: 100px; height: auto;">
</div>

<br>
