CREATE TABLE `traning`.`base_user` (
  `id` INT NOT NULL AUTO_INCREMENT COMMENT '主键id',
  `username` VARCHAR(10) NOT NULL COMMENT '名字',
  `email` VARCHAR(20) NOT NULL COMMENT '邮箱',
  `password` VARCHAR(20) NOT NULL DEFAULT 0,
  `ctime` timestamp NOT NULL DEFAULT CURRENT_TIMESTAMP COMMENT '创建时间',
  `mtime` timestamp NOT NULL DEFAULT CURRENT_TIMESTAMP ON UPDATE CURRENT_TIMESTAMP COMMENT '修改时间',
  PRIMARY KEY (`id`)
);
  
  
  