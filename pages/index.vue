<template>
<div>
    <div class="container">
      <div class="card-position2">
      <h2>ISTF</h2>
      <el-table :data="tableData" :show-header='false'>
        <el-table-column prop="date" label="Date">
        </el-table-column>
        <el-table-column prop="name" label="Name">
        </el-table-column>
        <el-table-column prop="address" label="Address">
        </el-table-column>
      </el-table>

      </div>

      <div class="card-position2">
      <h2>ISTP</h2>
      <el-table :data="tableData" :show-header='false'>
        <el-table-column prop="date" label="Date">
        </el-table-column>
        <el-table-column prop="name" label="Name">
        </el-table-column>
        <el-table-column prop="address" label="Address">
        </el-table-column>
      </el-table>
      </div>

      <div class="card-position2">
      <h2>ISFJ</h2>
      <el-table :data="tableData" :show-header='false'>
        <el-table-column prop="date" label="Date">
        </el-table-column>
        <el-table-column prop="name" label="Name">
        </el-table-column>
        <el-table-column prop="address" label="Address">
        </el-table-column>
      </el-table>
      </div>

      <div class="card-position2">
      <h2>ISFP</h2>
      <el-table :data="tableData" :show-header='false'>
        <el-table-column prop="date" label="Date">
        </el-table-column>
        <el-table-column prop="name" label="Name">
        </el-table-column>
        <el-table-column prop="address" label="Address">
        </el-table-column>
      </el-table>
      </div>

      <div class="card-position2">
      <h2>INTJ</h2>
      <el-table :data="tableData" :show-header='false'>
        <el-table-column prop="date" label="Date">
        </el-table-column>
        <el-table-column prop="name" label="Name">
        </el-table-column>
        <el-table-column prop="address" label="Address">
        </el-table-column>
      </el-table>
      </div>

      <div class="card-position2">
      <h2>INTP</h2>
      <el-table :data="tableData" :show-header='false'>
        <el-table-column prop="date" label="Date">
        </el-table-column>
        <el-table-column prop="name" label="Name">
        </el-table-column>
        <el-table-column prop="address" label="Address">
        </el-table-column>
      </el-table>
      </div>

      <div class="card-position2">
      <h2>INFJ</h2>
      <el-table :data="tableData" :show-header='false'>
        <el-table-column prop="date" label="Date">
        </el-table-column>
        <el-table-column prop="name" label="Name">
        </el-table-column>
        <el-table-column prop="address" label="Address">
        </el-table-column>
      </el-table>
      </div>

        <div class="card-position2">
      <h2>INFP</h2>
      <el-table :data="tableData" :show-header='false'>
        <el-table-column prop="date" label="Date">
        </el-table-column>
        <el-table-column prop="name" label="Name">
        </el-table-column>
        <el-table-column prop="address" label="Address">
        </el-table-column>
      </el-table>
      </div>

        <div class="card-position2">
      <h2>ESTJ</h2>
      <el-table :data="tableData" :show-header='false'>
        <el-table-column prop="date" label="Date">
        </el-table-column>
        <el-table-column prop="name" label="Name">
        </el-table-column>
        <el-table-column prop="address" label="Address">
        </el-table-column>
      </el-table>
      </div>

        <div class="card-position2">
      <h2>ESTP</h2>
      <el-table :data="tableData" :show-header='false'>
        <el-table-column prop="date" label="Date">
        </el-table-column>
        <el-table-column prop="name" label="Name">
        </el-table-column>
        <el-table-column prop="address" label="Address">
        </el-table-column>
      </el-table>
      </div>

        <div class="card-position2">
      <h2>ESFJ</h2>
      <el-table :data="tableData" :show-header='false'>
        <el-table-column prop="date" label="Date">
        </el-table-column>
        <el-table-column prop="name" label="Name">
        </el-table-column>
        <el-table-column prop="address" label="Address">
        </el-table-column>
      </el-table>
      </div>

        <div class="card-position2">
      <h2>ESFP</h2>
      <el-table :data="tableData" :show-header='false'>
        <el-table-column prop="date" label="Date">
        </el-table-column>
        <el-table-column prop="name" label="Name">
        </el-table-column>
        <el-table-column prop="address" label="Address">
        </el-table-column>
      </el-table>
      </div>

        <div class="card-position2">
      <h2>ENTJ</h2>
      <el-table :data="tableData" :show-header='false'>
        <el-table-column prop="date" label="Date">
        </el-table-column>
        <el-table-column prop="name" label="Name">
        </el-table-column>
        <el-table-column prop="address" label="Address">
        </el-table-column>
      </el-table>
      </div>

          <div class="card-position2">
      <h2>ENTP</h2>
      <el-table :data="tableData" :show-header='false'>
        <el-table-column prop="date" label="Date">
        </el-table-column>
        <el-table-column prop="name" label="Name">
        </el-table-column>
        <el-table-column prop="address" label="Address">
        </el-table-column>
      </el-table>
      </div>

        <div class="card-position2">
      <h2>ENFJ</h2>
      <el-table :data="tableData" :show-header='false'>
        <el-table-column prop="date" label="Date">
        </el-table-column>
        <el-table-column prop="name" label="Name">
        </el-table-column>
        <el-table-column prop="address" label="Address">
        </el-table-column>
      </el-table>
      </div>

        <div class="card-position2">
      <h2>ENFP</h2>
      <el-table :data="tableData" :show-header='false'>
        <el-table-column prop="date" label="Date">
        </el-table-column>
        <el-table-column prop="name" label="Name">
        </el-table-column>
        <el-table-column prop="address" label="Address">
        </el-table-column>
      </el-table>
      </div>

      
      <!-- <el-card class="box-card">
      <el-table :data="tableData">
        <el-table-column prop="date" label="Date">
        </el-table-column>
        <el-table-column prop="name" label="Name">
        </el-table-column>
        <el-table-column prop="address" label="Address">
        </el-table-column>
      </el-table>
      </el-card> -->
    </div>
</div>
</template>
<script>
  export default {
    data(){
      const item = {
        date: '2016-05-02',
        name: 'Tom',
        address: 'No. 189, Grove St'
      };
      return {
        tableData: Array(5).fill(item)
      }
    }
  };
</script>

<style scoped>
  .container{
    margin: 10px 0% 30px 10%;
    padding-top: 200px;
    
  }
    .card-position2{
    width: 45%;
    height: 480px;
    /* float: left; */
    display: inline-block;
  }

  @media only screen and (max-width: 1000px) {
  .container{
    margin: 0px 0% 0px 0%;
    padding-top: 250px;
    
  }
    .card-position2{
    width: 100%;
    height: 480px;
    /* float: left; */
    display: inline-block;
    
  }
}

  @media only screen and (max-width: 800px) {
  .container{
    margin: 0px 0% 0px 0%;
    padding-top: 10px;
    
  }

  }
  /* .box-card {
    width: 40%;
    height: 480px;
  } */
  /* .card-position{
    width: 40%;
    height: 480px;
    float: left;
  }

  .card-position2{
    width: 40%;
    height: 480px;
    float: left;
  } */
</style>