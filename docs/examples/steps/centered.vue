<template>
  <el-steps style="max-width: 600px" :active="2" align-center>
    <el-step title="调令生成" description="生成调拨单" />
    <el-step title="调令流转" description="代储责任单位已确认" />
    <el-step title="调令下发" description="调令下发到仓库管理单位" />
    <el-step title="调令实施" description="扫码出库" />
    <el-step title="调令收尾" description="提交归还请求" />
     <el-step title="完成" description="" />
  </el-steps>
</template>
