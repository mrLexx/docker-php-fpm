# Step for custom build

**Make excetute scripts in data dir:**

    chmod +x ./Dockerfiles/base/data/*
    chmod +x ./Dockerfiles/mods/data/*
    chmod +x ./Dockerfiles/prod/data/*
    chmod +x ./Dockerfiles/slim/data/*
    chmod +x ./Dockerfiles/work/data/*

**Make Dockerfiles**

    make gen-dockerfiles    

**Run build script**

    make build STAGE=base VERSION=X.X
    make build STAGE=mods VERSION=X.X
    make build STAGE=prod VERSION=X.X
    make build STAGE=slim VERSION=X.X
    make build STAGE=work VERSION=X.X

 
