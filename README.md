# nexus3
Docker compose to run nexus
ports:
      - "8081:8081" --->>>nexus UI
      - "8082:8082" --->>>nexus docker proxy  
      - "8083:8083" --->>>nexus docker host
