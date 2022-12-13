# PCI-Search-PowerShell
Script that searches for PCI data from a CSV file using regex

The difference between the patterns files is patternsKR is strictly looking for Korean-stype credit card numbers via a unique regex for their cards. The patterns2 file is a tested generic regex that covers Amex/Visa/MC/Discover/Diners Club with high confidence.

With patterns2, There is a tendency to pick up EU IBAN and EU Phone numbers as false positives because they can follow common credit card patterns, so you will need to manually verify hits.
