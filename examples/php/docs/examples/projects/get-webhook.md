<?php

use Appwrite\Client;
use Appwrite\Services\Projects;

$client = new Client();

$client
    ->setProject('')
;

$projects = new Projects($client);

$result = $projects->getWebhook('[PROJECT_ID]', '[WEBHOOK_ID]');