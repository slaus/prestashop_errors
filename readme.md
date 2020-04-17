Ошибка количества допустимых симоволов в характеристиках товаров в Prestashop 1.6
============

Действующие переменные
-------

| Command | Description |
| --- | --- |
| **/classes/Feature.php** | 'name' => array('type' => self::TYPE_STRING, 'lang' => true, 'validate' => 'isGenericName', 'required' => true, 'size' => 512) |
| **/classes/FeatureValue.php** | array('type' => self::TYPE_STRING, 'lang' => true, 'validate' => 'isGenericName', 'required' => true, 'size' => 2048) |
| **База данных** | команда ALTER TABLE `ps_feature_value_lang` CHANGE `value` `value` TEXT CHARACTER SET utf8 COLLATE utf8_general_ci NULL DEFAULT NULL; |
