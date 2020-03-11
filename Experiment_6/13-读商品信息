#include "lab52.h" // 请不要删除本行头文件，否则检查不通过
#include <stdio.h>
#include <stdlib.h>

extern int CurrentCnt; // 请不要删除本行的全局变量声明，否则检查不通过

GoodsInfo read_goods_info()
{
    GoodsInfo goodsInfo;
    printf("输入你要插入的商品信息：\n");
    printf("商品ID：");
    read_line(goodsInfo.goods_id, MAX_ID_LEN);
    printf("商品名称：");
    read_line(goodsInfo.goods_name, MAX_NAME_LEN);
    printf("商品价格：");
    scanf("%d", &goodsInfo.goods_price);
    printf("商品折扣：");
    read_line(goodsInfo.goods_discount, MAX_DISCOUNT_LEN);
    printf("商品数量：");
    scanf("%d", &goodsInfo.goods_amount);
    printf("商品剩余：");
    scanf("%d", &goodsInfo.goods_remain);
    return goodsInfo;
}
