{% data reusables.secret-scanning.api-beta %}

The {% data variables.product.prodname_secret_scanning %} API lets you{% ifversion fpt or ghec or ghes > 3.1 or ghae %}:

- Enable or disable {% data variables.product.prodname_secret_scanning %} for a repository. For more information, see "[Repositories](/rest/reference/repos#update-a-repository)" in the REST API documentation.
- Retrieve and update {% data variables.product.prodname_secret_scanning %} alerts from a {% ifversion fpt or ghec %}private {% endif %}repository. For futher details, see the sections below.
{%- else %} retrieve and update {% data variables.product.prodname_secret_scanning %} alerts from a {% ifversion fpt or ghec %}private {% endif %}repository.{% endif %}

For more information about {% data variables.product.prodname_secret_scanning %}, see "[About {% data variables.product.prodname_secret_scanning %}](/code-security/secret-security/about-secret-scanning)."