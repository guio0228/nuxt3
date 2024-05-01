<script setup lang='ts'>
//   let arr:Array<Number|String>=['aaa',131];
//   let arr1:(string | number)[]=['aaa',131];
// console.log(arr);

// interface Person{
//   name:string;
//   age:number;
//   sex?:string;
//   [propName:string]:any;
// }
// let putico:Person={
//   name:'putico',
//   age:18,
// }
// console.log(putico);
////////////////////////////////
// function Add(x: number, y: number): number;
// function Add(x: string, y: string): string;
// function Add(x: number | string, y: number | string): number | string {
//     if (typeof x === 'number' && typeof y === 'number') {
//         return x + y;
//     } else if (typeof x === 'string' && typeof y === 'string') {
//         return x + y;
//     } else {
//         throw new Error('Invalid argument types for Add function');
//     }
// }
// console.log(Add(1,2));
// console.log(Add('1','2'));
type stringType = '咪' | '喵' | '貓';

let str:stringType='咪';


</script>

<template>
  <div>
    <h2>456</h2>
  </div>
  
</template>



<style lang="scss" scoped>

</style>