# Цель: написать Ansible-роль, настраивающую связку nginx+php-fpm и выдающую при обращении к главной странице веб-сервера информацию о php (содержимое index.php — <?php phpinfo();?>).

## Создана роль в /etc/ansible/roles (/roles/main.yml в проекте)

## Создан playbook в /etc/ansible/playbooks (/playbooks/nginx_php_fpm.yml в проекте)

# Применение:
ansible-playbook /etc/ansible/playbooks/nginx_php_fpm.yml
