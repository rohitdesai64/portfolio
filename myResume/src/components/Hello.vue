<template>
  <div class="hello">
    
    <v-toolbar dark color="primary"></v-toolbar>

  <div class="px-3 py-4">
    <h2 class="headline text-xs-center pa-2" style="color: #6c68d9">About Me</h2>
    <v-layout>
      <v-flex xs5>
        <v-flex class="text-xs-center title grey--text">Job Profile</v-flex>
        <v-flex class="pa-2 subheading" style="line-height: 1.5;">The typography of an application is just as important as its functionality. 
          Vuetify.js uses the Material Design spec Roboto Font. Each heading size also has a 
          corresponding helper class to style other elements the same.</v-flex>
      </v-flex>
      <v-flex xs7>
        <table class="abt_table">
          <tr>
            <td>Age</td>
            <td>29</td>
          </tr>
          <tr>
            <td>Address: </td>
            <td>#18, '19A' Cross, C.M.H. Road, Laksmipuram, Halasuru.</td>
          </tr>
          <tr>
            <td>Permanent <Address></Address></td>
            <td>#68, Subhash Galli, Gandhinagar, Belgaum.</td>
          </tr>
          <tr>
            <td>E-mail</td>
            <td>rohit.desai64@gmail.com</td>
          </tr>
        </table>

      </v-flex>
    </v-layout>
  </div>


    <div class="px-3 py-4">
      <h2 class="headline text-xs-center pa-2" style="color: #6c68d9">Expierence</h2>
    <v-layout>
      <v-flex xs5 class="text-xs-center title grey--text">AriveGuru Technology Solutions Pvt. Ltd </v-flex>
      <v-flex xs7 class="pa-2 subheading" style="line-height: 1.5;">
        <ul>
          <li>Worked on HTML, CSS, JavaScript, Vue js</li>
          <li></li>
          <li></li>
          <li></li>
        </ul>
      </v-flex>
    </v-layout>

    </div>
  </div>
</template>
<style scoped>
.abt_table {
  font-size: 16px;
  color: #767676;
}
.abt_table td {
  padding: 10px;
}
.abt_table tr td:first-child {
  color: #767676;
  font-weight: 700
}
</style>

