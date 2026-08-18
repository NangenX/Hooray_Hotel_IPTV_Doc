# Guest H5 (Guest Self-Service)

> Introduction

![Guest H5](_images/guest/guest_1.png ':size=80%')

<!-- 📷 截图待补充：Guest H5 入口/首页 -->

`Guest H5` is a mobile web application for hotel guests. Guests open the page with their phone (via QR code or link) and can use the hotel IPTV services without touching the TV remote: watching live TV and VOD, ordering food, viewing the bill, requesting hotel services, and browsing facilities and nearby attractions.

## Access and Verification

![Guest H5 - Verify](_images/guest/guest_2.png ':size=80%')

<!-- 📷 截图待补充：客人验证页面 -->

The guest enters the **room number** and the **surname of the registered guest** on the verification page. The system checks the room and the surname (prefix match, case-insensitive), and creates an isolated guest session. The guest session is completely separated from the administrator session.

> **Note**: the guest session is per-browser and expires after a timeout. The guest must verify again after the session expires.

## Live TV

![Guest H5 - Live](_images/guest/guest_3.png ':size=80%')

<!-- 📷 截图待补充：H5 直播页面 -->

The guest can browse the live channel list and play the channels with the H5 player. The channel packages follow the same filtering rules as the set-top box: only the channels included in the room's purchased packages are displayed. Purchase is done on the TV or at the front desk; the H5 does not provide a purchase entry.

## Video On Demand

![Guest H5 - VOD](_images/guest/guest_4.png ':size=80%')

<!-- 📷 截图待补充：H5 点播页面 -->

The guest can browse VOD categories and movies, view the details (poster, introduction, year, region, click rate), and play the movie. When a movie has multiple episodes/lines, the guest can select the episode to play.

## Food Ordering

![Guest H5 - Food](_images/guest/guest_5.png ':size=80%')

<!-- 📷 截图待补充：H5 点餐页面 -->

The guest can browse the food categories and food items (with pictures, prices and descriptions), add items to the cart and submit the order. The order is pushed to the administrator console for confirmation. The guest can also view their order history and status.

## Bill

![Guest H5 - Bill](_images/guest/guest_6.png ':size=80%')

<!-- 📷 截图待补充：H5 账单页面 -->

The guest can view the current consumption bill, including the consumption records and the total amount, grouped by date.

## Hotel Services

![Guest H5 - Service](_images/guest/guest_7.png ':size=80%')

<!-- 📷 截图待补充：H5 酒店服务页面 -->

The guest can browse the hotel service categories and service items, and submit service reservations (e.g. room cleaning, laundry, wake-up call).

## Facilities & Surroundings

![Guest H5 - Facilities](_images/guest/guest_8.png ':size=80%')

<!-- 📷 截图待补充：H5 设施/周边页面 -->

The guest can browse the hotel facilities and surrounding attractions:

- **Facilities**: the facility content (e.g. swimming pool, gym, restaurant) is displayed as embedded pages.
- **Surroundings**: scenic spots around the hotel with pictures and introductions.

## Language

The H5 is bilingual (Chinese and English). Guests can switch the language on the page.
