        ArrayList<String> toReturn = new ArrayList<>();
        // find the next [, then find the ], then find the (, then read link upto next )
        int currentIndex = 0;
        while(currentIndex < markdown.length()) {
            int openBracket = markdown.indexOf("[", currentIndex);
            if(openBracket ==-1){
                break;
            }
            int closeBracket = markdown.indexOf("]", openBracket);
              if(closeBracket ==-1){
                break;
            }
            int openParen = markdown.indexOf("(", closeBracket);
            if(openParen ==-1){
                break;
            }
            int closeParen = markdown.indexOf(")", openParen);
            if(closeParen ==-1){
                break;
            }
            toReturn.add(markdown.substring(openParen + 1, closeParen));
            currentIndex = closeParen + 1;
        }
