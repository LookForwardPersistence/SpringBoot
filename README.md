# SpringBoot

### shiro 过滤路径注意事项
HashMap（无序）和双向链表合二为一即是LinkedHashMap（有序）
- 需要认证的路径写在后面
- 保证过滤路径有序 映射Map要使用LinkedHashMap
