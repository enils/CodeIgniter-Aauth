# Permission to Group Model

## Examples

## References

{% PHPclassDisplayer "Permission_to_group_model" %}
{% endPHPclassDisplayer %}

{% PHPmethodDisplayer "create($permission_id, $group_id)" %}
	Assigns a permission to a group.
	{% param "$permission_id", type="int" %}
	Permission's ID
	{% param "$group_id", type="int" %}
	Group's ID
	{% return %}
	Either `TRUE` on success, or `FALSE`.
{% endPHPmethodDisplayer %}

{% PHPmethodDisplayer "delete($permission_id, $group_id)" %}
	Removes a assigned permission from a group.
	{% param "$permission_id", type="int" %}
	Permission's ID
	{% param "$group_id", type="int" %}
	Group's ID
	{% return %}
	Either `TRUE` on success, or `FALSE`.
{% endPHPmethodDisplayer %}

{% PHPmethodDisplayer "delete_by_group($group_id)" %}
	Removes all assigned permissions from a group.
	{% param "$group_id", type="int" %}
	Group's ID
	{% return %}
	Either `TRUE` on success, or `FALSE`.
{% endPHPmethodDisplayer %}

{% PHPmethodDisplayer "delete_by_permission($permission_id)" %}
	Remove a permission from any group.
	{% param "$permission_id", type="int" %}
	Permission's ID
	{% return %}
	Either `TRUE` on success, or `FALSE`.
{% endPHPmethodDisplayer %}

{% PHPmethodDisplayer "exist($permission_id, $group_id)" %}
	Checks if a permission is already assigned to a group.
	{% param "$permission_id", type="int" %}
	Permission's ID
	{% param "$group_id", type="int" %}
	Group's ID
	{% return %}
	Either `TRUE` on success, or `FALSE`.
{% endPHPmethodDisplayer %}