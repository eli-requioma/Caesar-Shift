# Caesar-Shift
message = "the quick brown fox jumps over the lazy dog"
coded_message = "ldt gsxva nkjqi zjm hsbpu jctk ldt ryfw oje"

new_coded_message = "bw zycjkxlt vylu ykt bsivdaxiu yio udjkldyxku"

translated_string = ""
for i in range(len(new_coded_message)):
    character = new_coded_message[i]
    translated_character = message[coded_message.find(character)]
    translated_string = translated_string + translated_character
print(translated_string)
