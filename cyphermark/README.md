# 一，官方参考网页

cypher语句参考手册:[Neo4j Cypher Refcard 4.4](https://neo4j.com/docs/cypher-refcard/current/)

cypher语句详细介绍文档:[The Neo4j Cypher Manual v4.4 - Neo4j Cypher Manual](https://neo4j.com/docs/cypher-manual/current/)

neo4j总文档:[Neo4j documentation - Neo4j Documentation](https://neo4j.com/docs/)

# 二，目前用到的指令

删除所有节点：`MATCH (n) DETACH DELETE n`

查找有限个数节点:`MATCH (n) RETURN n LIMIT 25`

查找所有节点:`MATCH (n) RETURN n`

查找两个名字属性实体间的一层关系:`Match (n {NAME:"%ENT0%"})-[REL]->(m {NAME:"%ENT1%"}) return REL`
