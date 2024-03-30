<template>
<div class='grid grid-cols-2 gap-5 w-full h-full '>
    <div>
    <div class='max-h-[350px] overflow-auto'>
        <slot  name='markdown'></slot>
    </div>
        <small>Copia el código  y pégalo en Programiz 🚀</small>
    </div>
    <div class='max-h-[350px]'>
        <slot name='embed'>
         <iframe src="https://www.programiz.com/cpp-programming/online-compiler/"  style="border:0px #ffffff none;" name="programiz" frameborder="1" marginheight="0px" marginwidth="0px" height="100%" width="100%" allowfullscreen></iframe>
        </slot>
    </div>
</div>
</template>
