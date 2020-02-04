FROM bryne/spmiabaseimage
RUN mkdir -p /usr/local/transactionagentservice
ADD @project.build.finalName@.jar /usr/local/transactionagentservice/
ADD run.sh run.sh
RUN chmod +x run.sh
CMD ./run.sh
