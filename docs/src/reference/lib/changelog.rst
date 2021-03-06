Changelog
=========

0.2.2 (2020-12-11)
------------------

Fixed
*****

* Added support for writing an avro file via ``KlioWriteToAvro``
* Allow for support of empty ``job_config.data`` values for the built-in helper filter transforms.


0.2.1.post2 (2020-12-03)
------------------------

Fixed
*****

* Requires klio-core>=0.2.1 now that dependent changes have been released in new core version


0.2.1.post1 (2020-11-30)
------------------------

Fixed
*****

* Requires klio-core<0.2.1,>=0.2.0 to prevent useage of 0.2.1 until dependent code is released
* Klio lib requires changes not yet released in klio-core

0.2.1 (2020-11-24)
------------------------

Fixed
*****

* Handling of exceptions yielded by functions/methods decorated with @handle_klio
* KlioReadFromBigQuery rewritten as reader + map transform

0.2.0.post1 (2020-11-02)
------------------------

Fixed
*****

* Limited apache beam dependency to <2.25.0 due to a breaking change

0.2.0 (2020-10-02)
------------------

Initial public release!
