FROM gcr.io/cloud-builders/kubectl

COPY kustomize /builder/google-cloud-sdk/bin

RUN chmod +x /builder/google-cloud-sdk/bin/kustomize

ENTRYPOINT ["kustomize"]
