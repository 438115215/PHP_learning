# PHP_learning
## 1.完成php编写5种常用的排序算法，包括快速排序、冒泡排序、插入排序、选择排序、并归排序

 ### I  快速排序
 * 思想是设计2个块区，将数组分成小于基准数的数组和大于基准数的数组
 * 利用递归分治每层都处理一次left数组和right数组，直到递归出口，递归数组长度唯一的时候。
 * 这时就链接left和right数组
 
 ### II 冒泡排序
 * 本质是大数下沉小数上浮
 * 遍历数组外层循环表示趟数
 * 里层循环表示两数比对，大数下沉，小数上浮
 
 ### III 插入排序
 * 思想是假设前面的数是排序好的，之后是把后面n个数插入到前面的数中
 * 就像斗地主插牌一样
 
 ### IV 选择排序
 * 在要排序的一组数中，选出最小的一个数与第一个位置的数交换。
 * 然后在剩下的数当中再找最小的与第二个位置的数交换，
 * 如此循环到倒数第二个数和最后一个数比较为止。
 
 ### V 归并排序
 * 归并排序将待排序的序列分成若干组，
 * 保证每一组都有序。
 * 然后进行合并排序，最后整个序列都有序
 
 ## 2.完成使用PHPmailer发送邮件
 
 ## 3.完成使用QR-CODE生成二维码

 ## 4.完成使用递归的方式达成文件的遍历
 
 ## 5.完成生成迭代器对文件的读取
