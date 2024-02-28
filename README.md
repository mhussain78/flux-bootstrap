command to create secret

kubectl create secret generic api-token-ole  --from-literal=token=PAT from GutHub

kubectl create secret generic github-token --from-literal=token=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 --namespace default