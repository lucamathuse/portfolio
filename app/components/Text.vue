<template>
  <div class="wrapper my-24 flex flex-col gap-6">
    <div class="title">
      <h2>
        <slot name="title"></slot>
      </h2>
    </div>
    <div class="text">
      <p>
        <slot name="text"></slot>
      </p>  
    </div> 
  </div>
</template>

<style>

</style>