# Leak report

Memory errors were present because allocated memory was never freed. It is fixed by releasing the allocated memory before strip returns the result.
