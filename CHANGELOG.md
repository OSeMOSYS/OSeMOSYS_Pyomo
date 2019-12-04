# Open Source energy MOdeling SYStem

##  Main changes to previous version OSeMOSYS_2013_05_10

- Removed the parameter TechWithCapacityNeededToMeetPeakTS from constraint CAa4_Constraint_Capacity
- Fixed a bug related to using CapacityOfOneTechnologyUnit in constraint CAa5_TotalNewCapacity
- Fixed a bug in the storage equations which caused an error if more than one day type was used
- DiscountRate is no longer technology-specific. Therefore, DiscountRateStorage is now replaced by DiscountRate.