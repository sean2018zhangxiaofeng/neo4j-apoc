# neo4j-apoc
包含apoc图数据库Neo4j
neo4j 版本号： 3.4.6
apoc  版本号： 3.4.0.2

docker 运行命令：
  docker run -d -e NEO4J_dbms_security_procedures_unrestricted=apoc.* -p 7474:7474 -p 7473:7473 -p 7687:7687 --env=NEO4J_AUTH=neo4j/neo4j123456 --name neo4j-apoc qf/neo4j
