# memcacheQueue
PHP memcache 队列类

example:
$obj = new memcacheQueue('duilie');
$obj->add('1asdf');
$obj->getQueueLength();
$obj->read(10);
$obj->get(8);
