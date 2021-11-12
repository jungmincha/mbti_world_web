<template>
<div>
<div class="container">
    <header>
        <h2>MBTI 월드</h2>
        <div class="srchbtn"> 
        <el-input placeholder="관심 내용을 검색해보세요 :)">
         <el-button slot="append" icon="el-icon-search"></el-button>
        </el-input>
        </div>
        <div class="lgwrtbtn">
        <el-button type="success">로그인</el-button>
         <el-button type="info">글쓰기</el-button>
        </div>
        <!--header-nav-->
        <hr>
         <nav>
            <button>ISTJ</button>
            <button>ISTP</button>
            <button>ISFJ</button>
            <button>ISFP</button>
            <button>INTJ</button>
            <button>INTP</button>
            <button>INFJ</button>
            <button>INFP</button>
            <button>ESTJ</button>
            <button>ESTP</button>
            <button>ESFJ</button>
            <button>ESFP</button>
            <button>ENTJ</button>
            <button>ENTP</button>
            <button>ENFJ</button>
            <button>ENFP</button>
      </nav>
    </header>
    <!-- <el-row>
    <el-col :span="24"> -->

    <!-- </el-col>
    </el-row> -->
    <div class="main">
    <Nuxt/>
    </div>
    <div class="componentRoot">
        <footer>
        <div class='wrapCopyrightText'>
            <span class='copyrightText'>
            Copyright ©2021 mbti world Co., 대표자: 차정민
            </span>
        </div>
        </footer>
    </div>
    </div>
</div>
</template>

<script>
//   export default {
//     data() {
//       const item = {
//         date: '2016-05-02',
//         name: 'Tom',
//         address: 'No. 189, Grove St, Los Angeles'
//       };
//       return {
//         tableData: Array(20).fill(item)
//       }
//     }
//   };
</script>

<style>

  header {
    /* background-color: #B3C0D1; */
    /* color: #333; */
    line-height: 20px;
    text-align: left;
    border-radius: 4px;  
    background-color: white;
    position: relative; z-index: 2;
    	position:fixed;
	    width:100%;
	    top:0;
	    left:0;
  }
/* css 상속 */
  header h2{
    margin-left: 10%;
    display: inline-block;
  }

  header .srchbtn{
      display: inline-block;
      width: 300px;
      margin-left: 500px;
  }

  header .lgwrtbtn{
    display: inline-block;
  }

  /* .el-button{
      display: inline-block;
     
  } */
/* 
  .srchbtn .el-input{
     display: inline-block;
  } */

  /* .el-footer {
    background-color: #B3C0D1;
    background: #d3dce6;
    line-height: 60px;
  } */
  /* .el-row {
    margin-bottom: 20px;
  }
  .el-col {
    border-radius: 4px;
  } */
  /* .nav-header {
    background: #d3dce6;
    margin-bottom: 20px;
    border-radius: 4px;
  } */
  
  .componentRoot{
  margin-top: 2rem;
  
}

.wrapCopyrightText{
  background-color: #d3dce6;
  height: 5rem;
  display: flex;
  justify-content: center;
  align-items: center;

}


.copyrightText{
  position: center;
  font-size: 0.7rem;
  color: #1d242d;
}
  /* .grid-content {
    border-radius: 4px;
    height: 40px;
  } */
  /* nav {
    display: flex;
    justify-content: space-around;
}
nav {
  margin-bottom: 1rem;
} */

/* button {
  border: none;
  background-color: transparent;
  color: #898989;
  line-height: 40px;
} */
/* button:hover{
  color: black;
} */
nav {
  text-align: center;
     background: #d3dce6;
    margin-bottom: 20px;
    border-radius: 4px;
} 
nav button{
  border: none;
  background-color: transparent;
  color: #898989;
  line-height: 40px;
  margin-right: 20px;
  cursor: pointer;
  display: inline;
  text-align: center;
}

nav button:hover{
    color: black;
}

  @media only screen and (max-width: 1250px) {

  .main {
    padding-top: 40px;
  }

  header h2{
    margin-left: 0%;
    display: inline-block;
  }

  header .srchbtn{
      display: inline-block;
      width: 200px;
      margin-left: 10px;
  }

  header .lgwrtbtn{
    display: inline-block;
  }
}


  @media only screen and (max-width: 800px) {
      header {
        line-height: 20px;
        text-align: left;
        border-radius: 4px;  
        background-color: white;
        position: static;
  }

  }


/* nav button:visited{
    color: black;
} */

/* nav button{
  color:crimson;
}

nav button:hover {
  color:darksalmon;
  
}

nav button:active{
  transform: scale(0.98);
} */
</style>