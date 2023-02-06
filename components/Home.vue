<template>
  <div class="page-wrapper">
    <div class="container mx-auto px-4 md:px-0">
      <div class="w-full md:w-[500px] mx-auto flex items-end gap-4 my-[20px]">
        <div
          class="my-avart w-[165px] h-[165px] rounded-[10px] overflow-hidden mx-auto shadow-inner"
        >
          <img
            class="w-full h-full object-cover"
            :src="require(`~/static/images/avatar.jpg`)"
          />
        </div>
        <div class="flex-1">
          <div class="font-semibold text-lg pl-[1px]">nam lee @boiz_alime</div>
          <div class="flex items-center gap-1 my-3 text-gray-200">
            <ion-icon name="location-sharp"></ion-icon>
            <span class="text-[12px] font-bold">hochiminh city</span>
          </div>

          <div class="flex items-center gap-3">
            <ion-icon class="text-[22px]" name="mail-outline"></ion-icon>
            <ion-icon class="text-[22px]" name="logo-facebook"></ion-icon>
            <ion-icon class="text-[22px]" name="logo-youtube"></ion-icon>
            <ion-icon class="text-[22px]" name="logo-tiktok"></ion-icon>
            <ion-icon class="text-[22px]" name="logo-instagram"></ion-icon>
          </div>
        </div>
      </div>

      <div class="flex justify-center items-center flex-col gap-3">
        <div class="w-full md:w-[500px] mx-auto">
          <h1 class="text-[25px] font-bold">About me</h1>
          <div>
            Halo mng, mình là <span class="font-bold">N4m</span>, hiện tại thì
            mình đang là một
            <span class="font-bold">FullstackOverflow Developer</span> ở tp Hồ
            Chí Minh, mỗi ngày sau 8 tiếng code dưỡng sinh thì sở thích của mình
            là edit linh tinh, chơi game, nghe nhạc, xem phim, viết blog và nấu
            ăn.
          </div>

          <h1 class="text-[25px] font-bold my-2">Contact me</h1>
          <div class="flex flex-col gap-4">
            <button
              class="flex items-center w-full border rounded-[18px] px-4 py-2 hover:backdrop-blur-md transition-all"
            >
              <ion-icon class="text-[22px]" name="logo-youtube"></ion-icon>
              <span class="flex-1 font-bold text-center">youtube</span>
            </button>
            <a
              target="_blank"
              href="https://www.facebook.com/5x7xx/"
              class="flex items-center w-full border rounded-[18px] px-4 py-2 hover:backdrop-blur-md transition-all"
            >
              <ion-icon class="text-[22px]" name="logo-facebook"></ion-icon>
              <span class="flex-1 font-bold text-center">facebook</span>
            </a>
            <button
              class="flex items-center w-full border rounded-[18px] px-4 py-2 hover:backdrop-blur-md transition-all"
            >
              <ion-icon class="text-[22px]" name="mail-outline"></ion-icon>
              <span class="flex-1 font-bold text-center">mail</span>
            </button>
          </div>

          <!-- <div class="mt-4">
            tóm tăt:
            <ul>
              <li>- được cái chơi game ngu nhưng hơi toxic.</li>
              <li>- master chef món trứng rán và mì xào.</li>
              <li>- hướng nội nhưng thích giao lưu.</li>
              <li>- thích viết blog vl nhưng lười.</li>
              <li>- hay sai chính tả.</li>
              <li>- boiz alime.</li>
            </ul>
          </div> -->
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: 'HomePage',
}
</script>
