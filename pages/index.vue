<template lang="pug">
.w-full.relative.mt-4.shadow-2xl.rounded.my-24.overflow-hidden
  .top.h-64.w-full.bg-blue-600.overflow-hidden.relative
    img.bg.w-full.h-full.object-cover.object-center.absolute.z-0(src="https://wallpaperaccess.com/full/1867142.jpg" alt="")
    .flex.flex-col.justify-center.relative.h-full.bg-black.bg-opacity-50.text-white.pl-6
      img.h-36.w-60.object-cover.rounded-lg.border-2(src="https://scontent.fbkk5-1.fna.fbcdn.net/v/t1.15752-9/259401406_410260017522388_1456658837909761865_n.jpg?_nc_cat=109&ccb=1-5&_nc_sid=ae9488&_nc_ohc=LvB6UeN7faMAX8EM-AL&_nc_ht=scontent.fbkk5-1.fna&oh=03_AVJNnOZo-mdMKSFBbjdOxeMjGDZQCDkjlfTgx0Kg8jrBmA&oe=622F2CD2")
      h1.text-2xl.font-bold-500.uppercase.pt-4.fo Verayutt Pakpume

  .grid.grid-cols-12.bg-white
    .col-span-12.w-full.px-3.py-6.justify-center.flex.space-x-4.border-b.border-solid(class="md:space-x-0 md:space-y-4 md:flex-col md:col-span-2 md:justify-start")
      nuxt-link.text-sm.p-2.bg-black.text-white.text-center.rounded.font-bold(to="/" class="hover:bg-black hover:text-gray-200") Basic Information
      nuxt-link.text-sm.p-2.bg-indigo-200.text-center.rounded.font-semibold(to="/Information" class="hover:bg-black hover:text-gray-200") Another Information
      nuxt-link.text-sm.p-2.bg-indigo-200.text-center.rounded.font-semibold(to="/Something" class="hover:bg-black hover:text-gray-200") Another Something

    .col-span-12.h-full.pb-12(class="md:border-solid md:border-l md:border-black md:border-opacity-25 md:col-span-10")
      .px-4.pt-4
        form.flex.flex-col.space-y-7(action="#")
          div
            h3.text-2xl.font-bold Basic Information
            hr
          .form-item
            label.text-xl.font-semibold Full Name
            input.w-full.appearance-none.text-black.text-opacity-50.rounded.shadow.py-1.px-2.mr-2(type="text" value="Verayutt Pakpume ( วีรยุทธ ภาคภูมิ )" class="focus:outline-none focus:shadow-outline focus:border-blue-200" disabled="")
          .flex.flex-col.space-y-4(class="md:space-y-0 md:flex-row md:space-x-4")
            .form-item.w-full
              label.text-xl.font-semibold  Nickname
              input.w-full.appearance-none.text-black.text-opacity-50.rounded.shadow.py-1.px-2.mr-2.text-opacity-25(type="text" value="Jame  ( เจมส์ )" class="focus:outline-none focus:shadow-outline focus:border-blue-200" disabled="")
            .form-item.w-full
              label.text-xl.font-semibold  Email
              input.w-full.appearance-none.text-black.text-opacity-50.rounded.shadow.py-1.px-2.mr-2.text-opacity-25(type="text" value="overact150@gmail.com" class="focus:outline-none focus:shadow-outline focus:border-blue-200" disabled="")
          div
            h3.text-2xl.font-semibold More About Me
            hr
          div.pt
            p Date of birth : September 20, 2000
            p Address : Sukhothai, Thailand County.
            p Phone : + 66 964 342 588

          .form-item.w-full
            label.text-xl.font-semibold Biography
            textarea.w-full.appearance-none.text-black.text-opacity-50.rounded.shadow.py-1.px-2.mr-2.text-opacity-25(cols="30" rows="10" class="focus:outline-none focus:shadow-outline focus:border-blue-200" disabled="") Hello my name is James, now I am looking for an internship place for me. to practice new skills and challenges 

          div
            h3.text-2xl.font-semibold My Social Media
            hr
          .form-item
            label.text-xl Facebook
            input.w-full.appearance-none.text-black.text-opacity-50.rounded.shadow.py-1.px-2.mr-2.text-opacity-25(type="text" value="https://facebook.com/pinkcooooo/" class="focus:outline-none focus:shadow-outline focus:border-blue-200" disabled="")
          .form-item
            label.text-xl Gitlab
            input.w-full.appearance-none.text-black.text-opacity-50.rounded.shadow.py-1.px-2.mr-2(type="text" value="https://gitlab.com/overact150" class="focus:outline-none focus:shadow-outline focus:border-blue-200" disabled="")
</template>


<style scoped>
@import url('https://fonts.googleapis.com/css2?family=Rammetto+One&family=Rowdies:wght@700&display=swap');

.fo {
  font-family: 'Rammetto One', cursive;
  font-size: 18px;
}
</style>