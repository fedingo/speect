######################################################################################
##                                                                                  ##
## AUTHOR  : Aby Louw                                                               ##
## DATE    : 11 June 2010                                                           ##
##                                                                                  ##
######################################################################################
##                                                                                  ##
## CMakeList for nlp feature processors plug-ins                                    ##
##                                                                                  ##
##                                                                                  ##
######################################################################################

#------------------------------------------------------------------------------------#
#                        Plug-in directories                                         #
#------------------------------------------------------------------------------------#

add_subdirectory(accent)
add_subdirectory(breakindex)
add_subdirectory(endtone)
add_subdirectory(punctuation)
add_subdirectory(segment_duration)
add_subdirectory(segment_end)
add_subdirectory(segment_mid)
add_subdirectory(segment_name_multilingual)
add_subdirectory(segment_pos_syl)
add_subdirectory(segment_pos_syl_rev)
add_subdirectory(segment_pos_word)
add_subdirectory(segment_phoneset_feature)
add_subdirectory(segment_start)
add_subdirectory(syl_acc_in_phrase)
add_subdirectory(syllable_break)
add_subdirectory(syllable_break_marytts)
add_subdirectory(syllable_duration)
add_subdirectory(syllable_end)
add_subdirectory(syllable_num_phones)
add_subdirectory(syllable_pos_type)
add_subdirectory(syllable_pos_word)
add_subdirectory(syllable_pos_word_rev)
add_subdirectory(syllable_pos_phrase)
add_subdirectory(syllable_pos_phrase_rev)
add_subdirectory(syllable_start)
add_subdirectory(syllable_vowel)
add_subdirectory(syllable_stress_in)
add_subdirectory(syllable_stress_out)
add_subdirectory(syllable_accent_in)
add_subdirectory(syllable_accent_out)
add_subdirectory(syllable_stress_all_in)
add_subdirectory(syllable_stress_all_out)
add_subdirectory(syllable_accent_all_in)
add_subdirectory(syllable_accent_all_out)
add_subdirectory(word_break)
add_subdirectory(word_duration)
add_subdirectory(word_end)
add_subdirectory(word_num_syls)
add_subdirectory(word_num_phones)
add_subdirectory(word_pos_phrase)
add_subdirectory(word_pos_phrase_rev)
add_subdirectory(word_start)
add_subdirectory(word_content_in)
add_subdirectory(word_content_out)
add_subdirectory(word_content_all_in)
add_subdirectory(word_content_all_out)
add_subdirectory(words_from_phrase_start)
add_subdirectory(words_from_phrase_end)
add_subdirectory(words_from_utterance_start)
add_subdirectory(words_from_utterance_end)
add_subdirectory(phrase_num_syls)
add_subdirectory(phrase_num_words)
add_subdirectory(phrase_pos_utt)
add_subdirectory(phrase_pos_utt_rev)
add_subdirectory(phrase_endtone)
add_subdirectory(phrase_punc)
add_subdirectory(phrase_type)
add_subdirectory(utt_num_syls)
add_subdirectory(utt_num_words)
add_subdirectory(utt_num_phrases)
add_subdirectory(hts_labels)
