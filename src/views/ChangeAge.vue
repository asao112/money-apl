<template>
<div class="newQuestion">  
  <h1 class="subText1">変更する年齢を入力してください</h1>
  <form>
      <ul id="Q">
        <li class="Q4">
          <label id="Q4"><span>現在の年齢</span><br>age</label>
          <table><input type="number" id="question4" placeholder="現在の年齢を入力してください" v-model="question4" />
          <label>Please enter your age</label>
          </table>
        </li>
      </ul>
    </form>
    <router-link to="/myhome"><button class="button is-info is-outlined type6">登録</button></router-link>
</div>
</template>
<script>
export default {
  name: 'Register',
  data() {
    return {
      question4: '',
    };
  },
};
</script>