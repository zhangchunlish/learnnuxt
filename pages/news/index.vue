<template>
  <div>
      <h2>News Index page</h2>
      <p>NewsID:{{$route.params.newsId}}</p>
       <ul>
        <li><a href="/">Home</a></li>
        <li>
          <nuxt-link :to="{name:'news-id',params:{id:1233,title:'jspang.com'}}">News-1</nuxt-link>
        </li>
        <li>
          <nuxt-link :to="{name:'news-id',params:{id:4563,title:'zcl.com'}}">News-1</nuxt-link>
        </li>
       
      </ul>
  </div>
</template>

