Validate your metadata implementation
------------

After following these instructions, you should appear on the virtual platform. Check if your resource is listed here [`link <https://vp.ejprarediseases.org/discovery/sources>`_].  If you are still facing issues with the presentation of your resource in the platform, or if it does not appear at all, consider validating your metadata using the following method:

1. Add your FDP URL at the end of the link, following ‘?subject=’: http://testbed.ejprd.semlab-leiden.nl:40000/tests/ejp_base_metadata?subject=**YOUR_FDP_HERE**
2. Open the link to view your test results at the top (FAIL/SUCCESS). In case of FAIL, several warning messages (in orange) will appear, providing information about the missing metadata properties, as exemplified in the figure below.
..  figure:: _images/validator_1.png
    :alt:  Resulting screen of the validator, in case of failure.
    :width: 100%

    Figure - Resulting screen of the validator, in case of failure.
3. Based on the test feedback, you can either add the missing information yourself or contact the onboarding team for support. Once all the fixes are made, refresh the page to receive a success message.
..  figure:: _images/validator_2.png
    :alt:  Resulting screen of the validator, in case of success.
    :width: 100%

    Figure - Resulting screen of the validator, in case of success.


Validate L2 implementation:
~~~~~

If you have set up a beacon2 endpoint, the Virtual Platform needs to discover it through your FAIR Data Point (FDP) metadata. For that reason, a service similar to the one used for validating L1 implementations is available for testing your Beacon2 deployment metadata. The rationale is the same, with the only difference being the assessment link.

To run this test, add your FDP URL after 'subject=' in the following link: http://testbed.ejprd.semlab-leiden.nl:40000/tests/ejp_dataservice?subject=**YOUR_FDP_HERE**

Please note that this points to the FAIR Data Point implementation, not the Beacon2 endpoint itself.
