<template>
  <section id="schedule" class="schedule--main">
    <h1 class="section--title with-leaf">SCHEDULE</h1>
    <table class="schedule--table" border="1">
      <tr>
        <th></th>
        <th>月</th>
        <th>火</th>
        <th>水</th>
        <th>木</th>
        <th>金</th>
        <th>土</th>
        <th>日</th>
      </tr>
      <tr>
        <td>10:00-10:50</td>
        <td>国語</td>
        <td>国語</td>
        <td>国語</td>
        <td>国語</td>
        <td>国語</td>
        <td>国語</td>
        <td>国語</td>
      </tr>
      <tr>
        <td>10:00-10:50</td>
        <td>算数</td>
        <td>算数</td>
        <td>算数</td>
        <td>算数</td>
        <td>算数</td>
        <td>算数</td>
        <td>算数</td>
      </tr>
      <tr>
        <td>10:00-10:50</td>
        <td>理科</td>
        <td>理科</td>
        <td>理科</td>
        <td>理科</td>
        <td>理科</td>
        <td>理科</td>
        <td>理科</td>
      </tr>
      <tr>
        <td>10:00-10:50</td>
        <td>社会</td>
        <td>社会</td>
        <td>社会</td>
        <td>社会</td>
        <td>社会</td>
        <td>社会</td>
        <td>社会</td>
      </tr>
      <tr>
        <td>10:00-10:50</td>
        <td>英語</td>
        <td>英語</td>
        <td>英語</td>
        <td>英語</td>
        <td>英語</td>
        <td>英語</td>
        <td>英語</td>
      </tr>
      <tr>
        <td>10:00-10:50</td>
        <td>英語</td>
        <td>英語</td>
        <td>英語</td>
        <td>英語</td>
        <td>英語</td>
        <td>英語</td>
        <td>英語</td>
      </tr>
      <tr>
        <td>10:00-10:50</td>
        <td>数学</td>
        <td>数学</td>
        <td>数学</td>
        <td>数学</td>
        <td>数学</td>
        <td>数学</td>
        <td>数学</td>
      </tr>
    </table>
  </section>
  <!--end #schedule-->
</template>


<style lang="scss" scoped>
@import "../css/variables/variables.scss";
@import "../css/variables/colors.scss";

/* schedule */
.schedule {
  &--table {
    max-width: $width-sm;
    @media (min-width: $viewport-md) {
      max-width: $width-md;
    }

    & tr {
      & th,
      & td {
        text-align: center;
        padding: 0.5rem;
      }

      & th {
        font-size: 1.2rem;
      }
    }

    & tr:nth-child(odd) {
      background-color: rgba($primary-color-light, 0.5);
    }
  }
}
.schedule--main {
  position: relative;
  padding: 56px 0;
  z-index: 3;
  display: flex;
  justify-content: center;
  align-items: center;
  flex-direction: column;
}
</style>
