update:
	helm3 template \
	    datadog \
		--namespace=monitoring \
		--values datadog.values.yaml \
		vendor/stable/datadog-2.3.14/ \
		> datadog.yaml