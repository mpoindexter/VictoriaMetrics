FROM scratch
COPY --from=local/certs:1.0.3 /etc/ssl/certs/ca-certificates.crt /etc/ssl/certs/ca-certificates.crt
COPY bin/vmbackup-prod .
EXPOSE 8428
ENTRYPOINT ["/vmbackup-prod"]
