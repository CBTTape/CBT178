# CBT178
Converted to GitHub via [cbt2git](https://github.com/wizardofzos/cbt2git)

This is still a work in progress. 
Due to amazing work by Alison Zhang and Jake Choi repos are no longer deleted.

```
//***FILE 178 IS AN IDMS IPCS INTERFACE FROM NEAL KOSTANSKI OF      *   FILE 178
//*           ROSS LABORATORIES IN COLUMBUS, OHIO.  IF YOUR SHOP    *   FILE 178
//*           HAS IDMS, THIS CAN BE VERY USEFUL.                    *   FILE 178
//*                                                                 *   FILE 178
//*     THE CLISTS PROVIDED IN THIS PDS WILL PROCESS AN IPCS        *   FILE 178
//*     DUMP TAKEN FROM AN IDMS 10.2 SYSTEM.  THEY WILL PROVIDE     *   FILE 178
//*     A FORMATTED, AND IN SOME CASES, AN ENGLISH TRANSALATION     *   FILE 178
//*     OF THE CONTROL BLOCKS.  BELOW ARE SOME OF THE COMMANDS      *   FILE 178
//*     AND CONTROL BLOCKS WHICH CAN BE LOCATED, FORMATTED, AND     *   FILE 178
//*     DISPLAYED.                                                  *   FILE 178
//*                                                                 *   FILE 178
//*     THE IDMS CONTROL BLOCKS ARE DIVIDED INTO TWO                *   FILE 178
//*     CATEGORIES:  IDMS-DC AND IDMS DATABASE CONTROL              *   FILE 178
//*     BLOCKS AND ARE LISTED BELOW:                                *   FILE 178
//*                                                                 *   FILE 178
//*  DC - DATA COMMUNICATION PORTION OF DUMP - DEFAULT IF NO        *   FILE 178
//*              PARAMETER IS GIVEN ON THE EXEC STATEMENT           *   FILE 178
//*   CCE      - CENTRAL CONTROL BLOCK ELEMENT                      *   FILE 178
//*   CSA      - COMMON SYSTEM AREA                                 *   FILE 178
//*   DCE      - DISPATCH CONTROL ELEMENT                           *   FILE 178
//*   DCETCE   - DISPATCH CONTROL ELEMENT WITH ASSOCIATED TCE,      *   FILE 178
//*              RLE, AND RCE CHAINS DECODED.                       *   FILE 178
//*   ESE      - EXTERNAL SERVICE ELEMENT                           *   FILE 178
//*   ERE      - EXTERNAL REQUEST ELEMENT                           *   FILE 178
//*   ICE      - INTERVAL CONTROL ELEMENT                           *   FILE 178
//*   MAP      - REGION MAP ENTRIES                                 *   FILE 178
//*   LTT      - LOGICAL TERMINAL TABLE - FORMAT ALL LTE'S.         *   FILE 178
//*              PTE'S, RCE/RLE CHAIN WITH SOME TO BE ADDED LATER.  *   FILE 178
//*   NLT      - NUCLEUS LOAD TABLE                                 *   FILE 178
//*   RLEC     - RUN THE RLE-RCE CHAIN OFF OF THE CSA               *   FILE 178
//*   SCA      - SUBTASK CONTROL AREA AND ASSOCIATED TCE            *   FILE 178
//*   TCE      - CSECTACE TCE POINTED TO BY R9 IN THE CSECTACE      *   FILE 178
//*              WITH LTE, PTE, SON, RLE, & RCE                     *   FILE 178
//*   TRACE    - IDMS SYSTEM TRACE TABLE ENTRIES                    *   FILE 178
//*   VECTORS  - VECTOR TABLE OF ENTRY POINTS FOR IDMS MODULES      *   FILE 178
//*                                                                 *   FILE 178
//*  DB -  DATABASE CONTROL BLOCKS                                  *   FILE 178
//*   BC53     - BUFFER CONTROL ELEMENT                             *   FILE 178
//*   CLT      - CENTRAL LOCKING TABKE INCLUDING:                   *   FILE 178
//*              CLTE - CENTRAL LOCKING TABLE ELEMENTS              *   FILE 178
//*              SLT  - SYNONYM LOCKING TABLE HEADER                *   FILE 178
//*              SLTF - SYNONYM LOCKING TABLE FRAGMENTS             *   FILE 178
//*              LIDH - LOCK-UNIT TABLE HEADER                      *   FILE 178
//*              LIDF - LOCK-UNIT TABLE FRAGMENTS                   *   FILE 178
//*              LIDE - LOCK-UNIT TABLE ELEMENTS                    *   FILE 178
//*              RLTH - RUN-UNIT LOCK TABLE HEADER                  *   FILE 178
//*              RLTE - RUN-UNIT LOCK TABLE ELEMETS                 *   FILE 178
//*              RLTF - RUN-UNIT LOCK TABLE FRAGMENTS               *   FILE 178
//*   DM58     - DMCL TABLES HEADER                                 *   FILE 178
//*   FC59     - DMCL FILE CONTROL ELEMENTS                         *   FILE 178
//*   FM61     - DMCL FILE-AREA MEMBERSHIP                          *   FILE 178
//*   JD62     - JOURNAL CONTROL BLOCK                              *   FILE 178
//*   PR60     - DMCL AREA MAPPING ELEMENTS                         *   FILE 178
//*   VB50     - VARIABLE IB50 SUBSCHEMA CONTROL BLOCKS             *   FILE 178
//*                                                                 *   FILE 178
```
