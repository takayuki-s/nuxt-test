<template>
  <div>
    一覧表示<br>
    <NuxtLink to="/products/create">新規作成</NuxtLink>

    <table>
      <tr>
        <th>商品番号</th>
        <th>商品名</th>
        <th>詳細</th>
        <th>編集</th>
      </tr>
      <tr>
        <th>1</th>
        <th>テスト</th>
        <th><NuxtLink to="/products/1/show">詳細</NuxtLink></th>
        <th><NuxtLink to="/products/1/edit">編集</NuxtLink></th>
      </tr>
      <tr>
        <th>2</th>
        <th>テスト2</th>
        <th><NuxtLink to="/products/2/show">詳細</NuxtLink></th>
        <th><NuxtLink to="/products/2/edit">編集</NuxtLink></th>
      </tr>
    </table>
  </div>
</template>

<script>
</script>