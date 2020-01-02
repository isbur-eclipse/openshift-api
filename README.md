* используй nodejs-related стеки – а то даже git'a не найдёшь
    * git config --global push.default upstream
    * git config --global credential.helper store
    * git push --set-upstream origin master
    * (опционально) make файл отсюда: https://github.com/isbur/stub
        * wget https://raw.githubusercontent.com/isbur/stub/master/makefile

* добавить /projects/bin в $PATH
    * https://gist.github.com/nex3/c395b2f8fd4b02068be37c961301caa7
* wget https://mirror.openshift.com/pub/openshift-v4/clients/ocp/latest/openshift-client-linux-4.2.12.tar.gz
    * https://docs.openshift.com/container-platform/4.2/cli_reference/openshift_cli/getting-started-cli.html
    * https://cloud.redhat.com/openshift/install/metal/user-provisioned
    * https://mirror.openshift.com/pub/openshift-v4/clients/ocp/latest/
* tar -xzvf openshift-client-linux-4.2.12.tar.gz

* добавить /home/user/.local/bin в $PATH
    * vi ~/.bashrc
    * :w
    * :q
    * export PATH="/home/user/.local/bin:$PATH"
    * DAFUQ! Лучше попытаю счастья с другим базовым образом
