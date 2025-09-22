# vk_k8_filestore
k8_filestore

# Create File Store 

gcloud filestore instances create my-filestore \
    --project=<PROJECT_ID> \
    --zone=<ZONE> \
    --tier=STANDARD \
    --file-share=name="vol1",capacity=1TB \
    --network=name=<VPC_NETWORK>

gcloud filestore instances describe <INSTANCE_NAME> --zone=<ZONE>
