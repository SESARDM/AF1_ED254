AMAN and XMAN arrival sequence data should be based on the same validation schemas, but in the fact the XMAN servers suffer from a bug which have been worked around by marginally differentiating the validation schemas. The difference resides on the MeteringInformationType/amanEstimatedTimeOver element type :
- TimestampType for the SWIM AMAN service
- string for the SWIM XMAN service

But as soon as the bug is corrected, the validation should/will be identical.





