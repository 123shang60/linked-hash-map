# Linked-Hash_Map 

将底层修改为 DashMap 实现的版本

存在问题 ：

- 不支持原有的 `heapsize` 特性
- 仅支持实现 `Clone` 特性的 `BuildHasher`