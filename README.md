# Bootstrap-nested-menu-item-fix
This is a hack for bootsrap nav-walker menu. When menu is 'nested' with parent-child relationship, the parent-most top element becomes inactive and the anchor leads to "#".

When a child-theme is added to wordpress themes, functions.php needs to be added and a initialisaation to class-wp-bootstrap-navwalker.php file as well. class-wp-bootstrap-navwalker.php file has to be dropped in the root of the child-theme. 
