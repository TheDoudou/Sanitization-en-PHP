# Sanitization-en-PHP

    $options = array(
    'name' 			=> FILTER_SANITIZE_STRING,
    'lastName' 		=> FILTER_SANITIZE_STRING,
    'mail' 			=> FILTER_VALIDATE_EMAIL,
    'gender' 		=> FILTER_SANITIZE_STRING,
    'country' 		=> FILTER_SANITIZE_STRING,
    'subject' 		=> FILTER_SANITIZE_STRING,
    'message' 		=> FILTER_SANITIZE_STRING
